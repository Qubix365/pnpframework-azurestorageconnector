# AzureStorageConnector for PnP Framework

**AzureStorageConnector** is a [FileConnectorBase](https://github.com/pnp/pnpframework/blob/d7f3ff5aa75d2c2f54d92beddf55aaa51e748a0c/src/lib/PnP.Framework/Provisioning/Connectors/FileConnectorBase.cs) implementation (as a .NET Standard 2.0 / .NET 5.0 library) for [PnP Framework](https://github.com/pnp/pnpframework), and allows fetching provisioning templates from an Azure Blob Storage.

It is a modernized version of the new deprecated [AzureStorageConnector](https://github.com/pnp/PnP-Sites-Core/blob/deba8844ac45fa3e481ab11c66dfa4cd85489b4d/Core/OfficeDevPnP.Core/Framework/Provisioning/Connectors/AzureStorageConnector.cs) class that was part of PnP Framework's predecessor [PnP-Sites-Core](https://github.com/PnP/PnP-Sites-Core). 
Improvements over the original:
- Authentication through both connection string as well as [Azure.Identity](https://www.nuget.org/packages/Azure.Identity/)
- Replaces the unsupported [WindowsAzure.Storage](https://www.nuget.org/packages/WindowsAzure.Storage/) package with [Azure.Storage.Blobs](https://www.nuget.org/packages/Azure.Storage.Blobs)

## Getting started

Pull down the latest version of AzureStorageConnector here:

Nuget package | Description | Latest release
--------------|-------------|----------------
Qubix.PnPFramework.AzureStorageConnector | The AzureStorageConnector package | [![Qubix.PnPFramework.AzureStorageConnector Nuget package](https://img.shields.io/nuget/v/Qubix.PnPFramework.AzureStorageConnector.svg)](https://www.nuget.org/packages/Qubix.PnPFramework.AzureStorageConnector/)


## Building and contributing

To build AzureStorageConnector you need the following minimal components installed:

- [Visual Studio 2019 version 16.8+](https://visualstudio.microsoft.com/vs/)
- [.NET SDK version 5.0](https://dotnet.microsoft.com/download/dotnet/5.0)

Contributions should be made against the **dev** branch of the repository.