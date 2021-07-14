### Preparing IBM PowerVC Node:

1.  Install 'python3.6' and 'virtualenv'

2.  Install Python packages inside the Virtual Environment: ntpath, base64, pathlib, json, pycryptodome, ibm_boto3

3.  Make 'powervc-image' cmd. application available and place valid rc file under '/opt/ibm/powervc/powervcrc'

4.  Create sessions directory '/home/sessions' with enough storage to hold multiple disk images at once

### Add a PowerVS instance

1.  Add a PowerVS instance using Cloud Providers Tab in MIQ

2.  Initiate refreshing of the provider, wait to finish

### Add a PowerVC instance

1.  Add a PowerVC instance using Cloud Providers Tab in MIQ

2.  Go to Image Import Tab under the registration form

3.  Set the root password of the PowerVC node

4.  Initiate refreshing of the provider, wait to finish

### Add a Cloud Object Storage

1.  Add a Cloud Object Storage instance using Storage Providers Tab in MIQ

2.  Create a new bucket through IBM console or ibmcloud app, e.g. "transient-image-bucket"

3.  Initiate refreshing of the provider, wait to finish

### Start the workflow

1. Navigate to the newly added PVS instance 

2. Click on the "Import Image" button

3. Choose the newly added provider as a source for import

4. Choose the image you'd like to import

5. Choose cloud object storage

6. Choose a transient bucket

7. Choose target disk type for the image being imported

8. Decide if you want to keep transient OVA in your bucket after completion

9. Submit Request

10. You can see the progress in MIQ UI -> Settings -> Tasks -> All Tasks -> Running

11. Submit Inventory Refresh for all newly added providers upon completion


### Provision an instance

1. Navigate to PVS provider

2. Go to Images View and find the new image

3. Click on "Lifecycle -> Provision ..."

4. Follow instructions on doc. page: [reference]

5. Once the server is provisioned use SSH for connection

6. Do cat /etc/*rel* to see the release informaiton of the OS

