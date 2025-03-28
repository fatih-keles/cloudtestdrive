[Go to the Cloud Test Drive Welcomer Page](../../readme.md)

![](../../common/images/customer.logo2.png)

# Microservices on Kubernetes and Autonomous Database

## Setting up a CI/CD environment for developing Microservices on an ATP Database, with Developer Cloud

## Introduction

This lab will walk you through the steps to set up a CI/CD environment for developing Microservices, based on the automation possible in Developer Cloud and deploying all components on Oracle's Managed Container platform and the ATP database.

## Prerequisites

To run these labs you will need access to an Oracle Cloud Account.  We have prepared this lab for the following situations: 

- <u>You are using your own Oracle Cloud Tenancy,</u> either via a **Trial**, using a **Pay-as-you-Go** account, or using the **Corporate account** of your organization.  If you do not have an account yet, you can obtain  a [Free Trial account](https://myservices.us.oraclecloud.com/mycloud/signup?sourceType=:ow:evp:cpo::RC_EMMK190802P00026:VirtualLab_MicroservicesATP&intcmp=:ow:evp:cpo::RC_EMMK190802P00026:VirtualLab_MicroservicesATP).

  Next, follow the steps described on this page in the **Components of this lab** section.

  

- <u>You are joining an in-person Oracle event</u>: your instructor will provide you the required credentials to access an environment that has already been prepared with the minimum policies, account credentials etc.  
  
  ==> [Go to this page](../../ATP/readme.md) for detailed instructions



## Components of this lab

This lab is composed of the steps outlined below.  Please walk through the various labs in a sequential order, as the different steps depend on each other:

- [Preparing your Tenancy for the lab](env-setup.md) .
- [Provisioning an Autonomous Transaction Processing Database Instance](LabGuide100ProvisionAnATPDatabase.md)  using the OCI Console (manual).

  

You finished the setup part of your environment, and you can now start with the creation of your CI/CD flows in Developer Cloud:

- **Part 1:** [Setting up your Developer Cloud project](LabGuide250Devcs-proj.md)
- **Part 2:** [Create and populate the Database objects](LabGuide400DataLoadingIntoATP_own.md) in your ATP database with Developer Cloud
- **Part 3:** [Spin up a Managed Kubernetes environment with Terraform](LabGuide660OKE_Create.md)
- **Part 4:** [Build a Container image with the aone application running on ATP](LabGuide650BuildDocker.md)
- **Part 5:** [Deploy your container on top of your Kubernetes Cluster](LabGuide670DeployDocker.md)

---



[Go to the Cloud Test Drive Welcomer Page](../../readme.md)



#### [License](../../LICENSE)

Copyright (c) 2014, 2016 Oracle and/or its affiliates
The Universal Permissive License (UPL), Version 1.0