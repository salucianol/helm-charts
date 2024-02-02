# Helm Charts
Common repository for helm charts relating to Odoo ERP. You cna use it for free and also feel free to propose changes and improvements to this Charts.

## Common Chart
This common chart is for creating the Namespace and Storage Account to use when deploying one of the other charts contained within this repository.

> `helm install common-<version>`

## Odoo Chart
This chart deploys an Odoo application using either a private registry or the Docker Hub registry.

You can use the Common Chart to create the Storage Account and Namespace or, you can create it manually. In each case, you will need to give the values for the Name and Key for the Storage Account using the parameter `--set | --set-string` command line for `helm install`.

### Values.yaml: Coming soon...