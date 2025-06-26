# Guia Teórico de Criação de Máquinas Virtuais no Azure

## 1. Criar um Grupo de Recursos
Um grupo de recursos organiza os recursos do Azure:

Ex: "grupo-vm-estudo"

## 2. Criar uma Rede Virtual e Sub-rede
A rede permite a comunicação da VM com outros recursos e a internet.

- Rede: "vnet-estudo"
- Sub-rede: "subnet-vm"

## 3. Criar a Máquina Virtual

- Sistema: Ubuntu Server ou Windows Server
- Tamanho: Standard_B1s (uso leve)
- Usuário e senha ou chave SSH

## 4. Configurar a Porta de Acesso

- Porta 22 (Linux – SSH)
- Porta 3389 (Windows – RDP)

## 5. Validar e Criar
- Revisar configurações
- Criar e aguardar o provisionamento

## 6. Acessar a VM
- Linux: `ssh usuario@ip_publico`
- Windows: Usar aplicativo "Conexão de Área de Trabalho Remota"
