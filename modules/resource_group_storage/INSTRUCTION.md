# Terraform Azure Resource Group Storage Module

This module creates:

- Azure Resource Group
- Azure Storage Account

## Usage

```hcl
module "resource_group_storage" {
  source = "Loki-sudo007/resource_group_storage/azurerm"

  resource_group_name  = "my-resource-group"
  storage_account_name = "mystorageaccount123"
  location             = "East US"
}