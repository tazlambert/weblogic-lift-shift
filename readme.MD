# Welcome to Oracle WebLogic Lift and Shift Hands On Lab #

## About this hands-on Hands On Lab ##

This Hands On Lab main purpose is to show how to do lift and shift of existing WebLogic Domain so that WebLogic's user will be able to experience WebLogic's improvement on Oracle Cloud Infrastructure. This hands on lab is made based on the [OKE OCIR Demo](https://github.com/yyeung13/oke_ocir_demo/) also various references and has been tested by May 2020.

## Overview

In the following steps, you will be setting up a weblogic cluster that spans across two OCI Compute. The steps you will be performing includes:

- Provision first VM (weblogic1) on OCI using Oracle Linux Image  
- Install WebLogic Binary on the first VM  
- Configure a new clustered WebLogic Domain with 2 managed servers  
- Configure node manager for the first VM  
- Clone the boot volume of the first VM to be the boot volume of the second VM, and provision second VM (weblogic2) using the boot volume cloned  
- Prepare the second VM to join WebLogic Cluster  

### [Step 1: Provision first VM weblogic1 on OCI using Oracle Linux Images](provision.vm.compute.md)

### [Step 2: Enable Remote Display Access from Provisioned VM](enable.remote.display.oci.md)

### [Step 3: Install WebLogic Binary on the first VM](weblogic.installation.oci.md)

### [Step 4: Setup Cluster WebLogic Domain](weblogic.setup.cluster.oci.md)

### [Step 5: Provision OCI Load Balancer for Oracle WebLogic Cluster](provision.lb.oci.md)
