<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-azure-lb/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace Azure Load Balancer with Linux Virtual Machine Scale Set

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

Creates am Azure Load Balancer that serves traffic to Linux Virtual Machine Scale Set.

* Terraform Registry: [boltops-tools/lb](https://registry.terraform.io/modules/boltops-tools/lb/azure/latest)
* Azure Docs: [What is Azure Load Balancer?](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview)
* Azure Docs: [What are virtual machine scale sets?](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview)
* Terraform Docs: [azurerm_lb](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/lb)
* Terraform Docs: [azurerm_linux_virtual_machine_scale_set](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/linux_virtual_machine_scale_set)

## Env Vars

You should configure these env vars:

* ARM_CLIENT_ID
* ARM_CLIENT_SECRET
* ARM_SUBSCRIPTION_ID
* ARM_TENANT_ID

As covered in: [Terraspace Azure Getting Started Docs: Configure Azure](https://terraspace.cloud/docs/learn/azure/configure/)

## Deploy

To deploy:

    terraspace up linux_scaleset_lb

## Video

[![Watch the video](https://uploads-learn.boltops.com/6ovv756vvl78t195mtq6e6e7y1xh)](https://learn.boltops.com/courses/terraspace-azure/lessons/terraspace-azure-lb-load-balancer-with-virtual-machine-scale-set)

Note: Premium video content requires a subscription.
