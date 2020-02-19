#### Deploying a Red Hat OpenStack Platform 13 Director

This repository contains a playbook and a role used to automate the deployment 
of a RHOSP13 Director/Undercloud. 

#### Pre-Requisites

* A Red Hat Enterprise Linux 7 Virtual Machine. Director resource requirements are 
documented in the [Red Hat OpenStack Platform 13 Director Installation Guide](https://access.redhat.com/documentation/en-us/red_hat_openstack_platform/13/html/director_installation_and_usage/chap-requirements#sect-Undercloud_Requirements)
..* 2 x Network Interfaces | 1 x SSH/Management and 1 x Provisioning
* Access to a Red Hat Satellite Server
..* Satellite Organization
..* Activation Key
..* Access to the Red Hat Enterprise Linux Repositories used for the
installation of RHOSP 13
