---
ms.topic: include
ms.date: 09/10/2020
author: dbradish-microsoft
ms.author: dbradish
manager: barbkess
---

1. Locally [install](install-azure-cli.md) the Azure CLI or start [Azure Cloud Shell](start-azure-cloud-shell.md) to run Azure CLI commands.
1. Sign in using the [az login](/cli/azure/reference-index#az-login) command if you're using a local install of the CLI.  See [Sign in with Azure CLI](authenticate-azure-cli.md) for additional sign in options.

   ```azurecli
   az login
   ```

    Follow the steps displayed in your terminal to complete the authentication process.
1. If you do not have a resource group, create one using the [az group create](/cli/azure/group#az-group-create) command.  See [What is Azure Resource Manager](/azure/azure-resource-manager/management/overview) to learn more about resource groups.

   ```azurecli
   az group create --name myNewResourceGroupName --location eastus
   ```
