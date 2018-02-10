---
services: Compute
platforms: java
author: anuchandy
---

## Getting Started with Compute - List Compute Skus - in Java ##


  Azure Compute sample for managing Compute SKUs -
 
  - list all compute SKUs in the subscription
  - list compute SKUs for a specific compute resource type (VirtualMachines) in a region
  - List compute SKUs for a specific compute resource type (Disks).
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-list-compute-skus.git

    cd compute-java-list-compute-skus

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.