---
page_type: sample
languages:
- csharp
products:
- azure
- azure-virtual-machines
- azure-resource-manager
- dotnet
extensions:
- services: Resource-Manager
- platforms: dotnet
description: "Azure Resource sample for deploying virtual machine with managed disk using an ARM template."
urlFragment: getting-started-with-deploying-a-virtual-machine-with-managed-disks-using-an-arm-template-in-c
---

# Get started deploying a Virtual Machine with managed disks using an ARM Template (C#)

Azure Resource sample for deploying virtual machine with managed disk using an ARM template.

## Running this sample

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/resources-dotnet-deploy-virtual-machine-with-managed-disks-using-arm-template.git
cd resources-dotnet-deploy-virtual-machine-with-managed-disks-using-arm-template
dotnet build
bin\Debug\net452\DeployVirtualMachineUsingARMTemplate.exe
```

## More information

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
