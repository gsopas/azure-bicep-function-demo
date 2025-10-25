# ⚙️ Azure IaC Demo — Function App + Storage with Bicep

This project provisions a serverless environment using **Azure Bicep**.

## 🧩 Architecture
- Azure Resource Group
- Storage Account (Standard_LRS)
- Function App (Consumption Plan)

## 🚀 Deploy
```bash
az group create -n rg-bicep-demo -l australiaeast
az deployment group create --resource-group rg-bicep-demo --template-file main.bicep
