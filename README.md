# todoapp
K8-based three-tier application to be deployed on AKS and integrated with New Relic. 

######## Login to Azure Portal using CLI ################
az login

######## Create Resource Group using CLI ################
az group create --name MyResourceGroup --location eastus

########  Create an AKS Cluster ######## 
az aks create --resource-group MyResourceGroup --name SaurabhCluster --node-count 2 --enable-addons monitoring --generate-ssh-keys

