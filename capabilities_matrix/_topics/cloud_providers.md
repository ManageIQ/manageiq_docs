### Cloud Providers

The following table outline the status of support for {{ site.data.product.title_short }} features on various cloud providers.

| Feature                                    | Amazon Web Services (AWS) | Microsoft Azure | Google Cloud Platform (GCP) | Red Hat OpenStack Platform | IBM PowerVC via the OpenStack API     |
| ------------------------------------------ | ------------------------- | --------------- | --------------------------- | -------------------------- | ------------------------------------- |
| Relationship Discovery                     | Yes                       | Yes             | Yes                         | Yes                        | Yes                                   |
| Instance Drift Comparison                  | Yes                       | Yes             | No                          | Yes                        | No                                    |
| Track Instance Genealogy                   | Yes                       | Yes             | Yes                         | Yes                        | Yes                                   |
| Capacity & Utilization                     | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Capture Cloud Layer Timelines              | No                        | No              | No                          | Yes                        | Yes                                   |
| Capture Instance Event Timelines           | Yes                       | Yes             | Yes                         | Yes                        | Yes                                   |
| Discovery - Provider                       | Yes                       | Yes             | No                          | No                         | No                                    |
| Disk Addition to Instance                  | Yes                       | Yes             | No                          | Yes                        | No                                    |
| Key Pairs Inventory                        | Yes                       | No              | Yes                         | Yes                        | Yes                                   |
| Key Pairs Management                       | Yes                       | Yes             | No                          | Yes                        | Yes                                   |
| Reporting                                  | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Right Sizing                               | Yes                       | Yes             | Yes                         | Yes                        | Yes                                   |
| Chargeback                                 | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Remote Console Instance Access             | No                        | No              | No                          | Yes                        | Yes (for NovaLink-managed hosts only) |
| Snapshot Creation and Removal              | No                        | No              | No                          | Yes                        | Yes                                   |
| Instance Compliance Enforcement            | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Instance Policy Enforcement                | Yes                       | Yes             | Yes                         | Yes                        | Yes                                   |
| Instance Power Operations                  | Yes                       | Yes             | Yes                         | Yes                        | Yes                                   |
| Instance Retirement                        | Yes                       | Yes             | Yes                         | Yes                        | Yes                                   |
| Alerts - Real Time                         | No                        | No              | No                          | Yes                        | No                                    |
| Alerts - Instance Value Changed            | No                        | No              | No                          | No                         | No                                    |
| Alerts - Reconfigured                      | No                        | No              | No                          | No                         | No                                    |
| Integrate with Service Catalogs            | Yes                       | Yes             | Yes                         | Yes                        | Yes                                   |
| Instance Reconfiguration                   | No                        | No              | No                          | Yes                        | Yes                                   |
| Volume Inventory                           | No                        | No              | Yes                         | Yes                        | Yes                                   |
| Volume Creation/Deletion                   | No                        | No              | No                          | Yes                        | Yes                                   |
| Instance Migration                         | No                        | No              | No                          | Yes                        | Yes                                   |
| Automation Work Flows                      | Yes                       | No              | Yes                         | Yes                        | Yes                                   |
| Network Manager - Read Only                | No                        | Yes             | Yes                         | No                         | Yes                                   |
| Network Manager - CRUD Actions Supported   | No                        | No              | No                          | No                         | No                                    |
| Storage Manager                            | Yes                       | No              | No                          | Yes                        | No                                    |
| Provision from Template/Image to Instance  | Yes                       | Yes             | Yes                         | Yes                        | Yes                                   |
| Provision from Image Snapshot to Instance  | No                        | No              | No                          | Yes                        | No                                    |
| Provision from Volume to Instance          | No                        | No              | No                          | Yes                        | No                                    |
| Provision from Volume Snapshot to Instance | No                        | No              | No                          | Yes                        | No                                    |
| Orchestration Template Provisioning        | Yes                       | Yes             | No                          | Yes                        | No                                    |
| Cloud-Init                                 | No                        | No              | No                          | Yes                        | No                                    |
| Sysprep Windows Templates                  | No                        | No              | No                          | Yes                        | No                                    |
| Network Manager Relationships              | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Relationship Discovery                     | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Cloud Network Inventory                    | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Cloud Subnet Inventory                     | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Network Router Inventory                   | No                        | No              | Yes                         | Yes                        | No                                    |
| Security Groups                            | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Floating IP Addresses                      | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Network Ports                              | Yes                       | Yes             | Yes                         | Yes                        | No                                    |
| Load Balancer Inventory                    | Yes                       | Yes             | Yes                         | No                         | No                                    |
| Create/Update/Delete Network               | No                        | No              | No                          | Yes                        | No                                    |
| Create/Update/Delete Subnet                | No                        | No              | No                          | Yes                        | No                                    |
| Create/Update/Delete Routers               | No                        | No              | No                          | Yes                        | No                                    |