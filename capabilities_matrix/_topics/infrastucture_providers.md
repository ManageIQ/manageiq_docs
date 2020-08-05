### Infrastructure Providers Features Support

 The following table outline the status of support for {{ site.data.product.title_short }} features on various virtual infrastructure providers.

| Feature                                                      | VMware vSphere | Red Hat Virtualization (RHV) | Microsoft System Center Virtual Machine Manager (SCVMM) | OpenStack Platform (OSP) Director |
| ------------------------------------------------------------ | -------------- | ---------------------------- | ------------------------------------------------------- | --------------------------------- |
| Relationship Discovery                                       | Yes            | Yes                          | Yes                                                     | Yes                               |
| VM Drift Comparison                                          | Yes            | Yes                          | Yes                                                     | No                                |
| Track VM Genealogy                                           | Yes            | Yes                          | Yes                                                     | Yes                               |
| Capacity & Utilization                                       | Yes            | Yes                          | No                                                      | No                                |
| Capture VM/Instance Event Timelines                          | Yes            | Yes                          | Yes                                                     | No                                |
| Discovery - Provider                                         | Yes            | Yes                          | Yes                                                     | No                                |
| Reporting                                                    | Yes            | Yes                          | Yes                                                     | Yes                               |
| Right Sizing                                                 | Yes            | Yes                          | No                                                      | No                                |
| Chargeback                                                   | Yes            | Yes                          | Yes [a]                                                 | No                                |
| Remote Console VM Access [b]                                 | Yes            | Yes                          | Yes                                                     | No                                |
| Snapshot Creation and Removal                                | Yes            | Yes                          | No                                                      | No                                |
| VM / Instance Compliance Enforcement                         | Yes            | Yes                          | Yes                                                     | No                                |
| VM / Instance Policy Enforcement                             | Yes            | Yes                          | Yes                                                     | No                                |
| VM / Instance Power Operations                               | Yes            | Yes                          | Yes                                                     | No                                |
| VM / Instance Retirement                                     | Yes            | Yes                          | Yes                                                     | No                                |
| Alerts - Real Time                                           | Yes            | No                           | No                                                      | No                                |
| Alerts - VM Value Changed                                    | Yes            | Yes                          | No                                                      | No                                |
| Alerts - VM Reconfigured                                     | Yes            | Yes                          | No                                                      | No                                |
| Integrate with Service Catalogs                              | Yes            | Yes                          | Yes                                                     | No                                |
| Virtual Machine Reconfiguration                              | Yes            | Yes                          | No                                                      | No                                |
| Automation Work Flows                                        | Yes            | Yes                          | Yes                                                     | No                                |
| Provision VM/Instance using PXE                              | Yes            | Yes                          | No                                                      | No                                |
| Provision VM/Instance using ISO                              | No             | Yes                          | No                                                      | No                                |
| Provision from Template/Image to VM/Instance                 | Yes            | Yes                          | Yes                                                     | No                                |
| Provision from VM/Instance to Template/Image                 | Yes            | Yes                          | No                                                      | No                                |
| Clone from VM/Instance to VM/Instance                        | Yes            | No                           | No                                                      | No                                |
| Disk Addition to VM/Instance                                 | Yes            | No                           | No                                                      | No                                |
| Host Power Operations                                        | Yes            | No                           | No                                                      | No                                |
| Provision Host                                               | No             | No                           | No                                                      | No                                |
| Cloud-Init                                                   | No             | Yes                          | No                                                      | No                                |
| Customize Windows Templates with Sysprep during Provisioning | Yes            | Yes                          | No                                                      | No                                |
| OVN Provider                                                 | No             | Yes                          | No                                                      | No                                |
| Nodes Inventory                                              | No             | No                           | No                                                      | Yes                               |
| OpenStack Services Inventory                                 | No             | No                           | No                                                      | Yes                               |
| Nodes Drift Comparison                                       | No             | No                           | No                                                      | Yes                               |
| Nodes Smart State                                            | No             | No                           | No                                                      | Yes                               |
| Capacity & Utilization                                       | No             | No                           | No                                                      | Yes                               |
| Capture Infrastructure Event Timelines                       | No             | No                           | No                                                      | Yes                               |
| Node Power Operation                                         | No             | No                           | No                                                      | Yes                               |
| Capacity Planning                                            | No             | No                           | No                                                      | Yes                               |
| Add/Remove Node                                              | No             | No                           | No                                                      | Yes                               |
| Scale Down Node                                              | No             | No                           | No                                                      | Yes (Compute nodes only)          |
| Scale Up Nodes                                               | No             | No                           | No                                                      | Yes (Compute nodes only)          |
| Nodes Policy Enforcement                                     | No             | No                           | No                                                      | Yes                               |
| Nodes Evacuate                                               | No             | No                           | No                                                      | Yes                               |
| OpenStack Upgrade                                            | No             | No                           | No                                                      | No                                |


[a] Limited to inventory allocation.
[b] On some operating system and browser combinations.