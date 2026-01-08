##AZ-104 ARM Deployment Project

This project demonstrates how to deploy Azure resources using ARM templates and GitHub Actions. It covers:
- Virtual Network (VNet) with subnets
- Network Security Groups (NSGs)
- Virtual Machines (VMs)
- Storage Accounts

## Prerequisites
- Azure subscription
- Azure CLI or PowerShell
- GitHub account with repository secrets configured

## Deployment
Run:
```bash
az deployment group create --resource-group <RG_NAME> --template-file templates/vnet.json
