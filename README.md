---
services: Compute
platforms: .Net
author: anuchandy
---

# Getting Started with Compute - Manage Virtual Machines In Parallel With Network - in .Net #

          Create a virtual network with two Subnets – frontend and backend
          Frontend allows HTTP in and denies Internet out
          Backend denies Internet in and Internet out
          Create m Linux virtual machines in the frontend
          Create m Windows virtual machines in the backend.


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-net/blob/Fluent/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-dotnet-manage-virtual-machines-with-network-in-parallel.git

    cd compute-dotnet-manage-virtual-machines-with-network-in-parallel

    dotnet restore

    dotnet run

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.