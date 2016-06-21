# This template deploys multiple VMs behind a Load Balancer with NAT rules

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fwba-demo%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fwba-demo%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template deploys multiple Virtual Machines in an Availability Set and configures NAT rules through the Load Balancer.  This template also deploys Storage Accounts, Public IP address and Network Interfaces.

In this template, we use the resource loops capability to create the network interfaces and virtual machines.
