# Comandos Úteis em Azure CLI e PowerShell

## Azure CLI

```bash
# Login no Azure
az login

# Criar grupo de recursos
az group create --name grupo-vm --location eastus

# Criar uma VM Linux
az vm create \
  --resource-group grupo-vm \
  --name minhaVM \
  --image UbuntuLTS \
  --admin-username azureuser \
  --generate-ssh-keys

# Abrir porta para SSH
az vm open-port --port 22 --resource-group grupo-vm --name minhaVM
