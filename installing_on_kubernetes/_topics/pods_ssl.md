## Create a CA:
# Generate a key
openssl genrsa -des3 -out myCA.key 2048
# Generate CA Cert
openssl req -x509 -new -nodes -key myCA.key -sha256 -days 3650 -out myCA.pem


## For each service:
# Generate a key
openssl genrsa -out ui.key 2048
# Creating a signing request
openssl req -new -key ui.key -out ui.csr
# Sign it
openssl x509 -req -in ui.csr -CA myCA.pem -CAkey myCA.key -CAcreateserial -out ui.crt -days 825 -sha256



certificate_authority$ ls
myCA.key  myCA.pem  myCA.srl  test-ui.yml  ui.crt  ui.csr  ui.key

certificate_authority$ oc create secret generic certs-secret \
> --from-file=cacert=./myCA.pem \
> --from-file=ui_crt=./ui.crt \
> --from-file=ui_key=./ui.key \
> --from-file=ui_http_conf=./manageiq-http.conf
secret/certs-secret created
