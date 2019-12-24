# Azure Container Instance Hosted Minecraft Server
This Azure Resource Manager template, provides an easy to setup Minecraft server running on ACI. Due to the pricing model of ACI it is not recommend for running this server 24x7, but it is good for on demand play session. The world state is saved between server stop/starts in Azure File Storage. 

For more information see my blog post on the topic: https://wp.sjkp.dk/running-a-minecraft-server-on-azure-using-aci/

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsjkp%2Fazure-arm-aci-minecraft-server%2Fmaster%2Fazuredeploy.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>