# Getting started

The aim of this section is to point you in the right direction to get started within the C-SCALE ecosystem.

These pages are targeted to users already onboarded onto the C-SCALE federation. If you want to become a
user email `info<at>c-scale.eu`.

## Create a user account

### Cloud

For cloud providers that are part of the federation (CESNET, INFN Bari, GRNET, INCD) and VITO:

* Create an [EGI Account](https://docs.egi.eu/users/check-in/signup/)

For cloud providers that will be federated in the future

* Create an [EODC Account](https://eodc.eu/register)
* Create a [CloudFerro Account](https://portal.creodias.eu/register.php)

### HTC/HPC

For federated HTC/HPC providers (SURF, GRNET)

* Create a [SURF Account](https://sram.surf.nl/)
* Upload your public SSH key to the [SRAM portal](https://sram.surf.nl/profile)

More information about SRAM see the [SRAM wiki](https://wiki.surfnet.nl/display/SRAM/)

For HTC/HPC providers that will be federated in the future

* Create an [EODC Account](https://eodc.eu/register)

## Join user groups

At the moment we use two separate systems for managing user groups.
The future goal is to have user groups managed by a single platform.

### Cloud

The information about user groups for cloud services is available in
[EGI Operations Portal](https://operations-portal.egi.eu/vo/a/list). Search for "C-SCALE"
to find all the available groups:

* [Return](https://operations-portal.egi.eu/vo/view/voname/return.c-scale.eu)
* [Aquamonitor](https://operations-portal.egi.eu/vo/view/voname/aquamonitor.c-scale.eu)
* [HiSea](https://operations-portal.egi.eu/vo/view/voname/hisea.c-scale.eu)
* [LSDA](https://operations-portal.egi.eu/vo/view/voname/HighResLandSurf.c-scale.eu)

User groups in the cloud federation are also known as
[Virtual organisations](https://confluence.egi.eu/display/EGIG/Virtual+organisation)
(or VOs), and the links above are called VO ID Cards.

Users will have to visit the **enrollment URL** to request access. Each petition needs to
be approved by the corresponding VO manager. The enrollment URL and the VO manager for each
user group can be found in each VO Card.

### HTC/HPC

The information about user groups for HTC/HPC services is available in
[SRAM Collaborative Organisation (or COs)](https://sram.surf.nl/home/collaborations)

So far we have only created a single user group in SRAM for the HiSEA Use Case:

* [HiSea](https://sram.surf.nl/registration?collaboration=9b0a6184-326e-44d8-bc1d-903193b11f2b)

The link above is the **Join Request URL** that users will have to visit to
request access. Each petition needs to be approved by the corresponding CO Admin. 

## Access to services

### Cloud

* [GRNET OpenStack](https://ui.cloud.grnet.gr/)
* [EODC OpenStack](https://launcher.eodc.eu/)
* [CESNET OpenStack](https://dashboard.cloud.muni.cz/)
* [INFN Bari OpenStack](https://cloud.recas.ba.infn.it/)
* [INCD OpenStack](https://stratus.ncg.ingrid.pt/)
* [CloudFerro OpenStack](https://cf2.cloudferro.com/)
* VITO:
    * [Home page](https://terrascope.be/en )
    * [openEO login](https://docs.terrascope.be/#/Developers/WebServices/OpenEO/OpenEO?id=logging-in)

Cloud resources can also be deployed with the [INDIGO PaaS Orchestrator](https://indigo-paas.cloud.ba.infn.it/)

### HTC/HPC

* SURF:
    * Username: `sram-[CO short name]-[SRAM username]`
    * Connect via: `ssh -YC sram-[CO short name]-[SRAM username]@delena.surfsara.nl`
* [EODC VSC](https://support.eodc.eu/kb/faq.php?id=18)
* [GRNET Aris](https://doc.aris.grnet.gr/login/)

## Providers documentation

### Cloud

* [GRNET OpenStack Documentation](https://help.cloud.grnet.gr/)
    * [Create a VM](https://help.cloud.grnet.gr/t/create-a-vm-instance/)
* [EODC Openstack Knowledgebase](https://support.eodc.eu/kb/faq.php?cid=6)
* INCD
    * [Tutorial Openstack Dashboard](https://docs.google.com/presentation/d/1yERFe9v5xupjPJcZAnVdI1kmKXg4nlb3MlTZIYviVHQ/)
    * [Tutorial Openstack CLI](https://lip-computing.github.io/tutorials/openstack-cli/oscli.html)
* CESNET: TBD
* INFN Bari: TBD
* [CloudFerro FAQ](https://creodias.eu/faq)
* VITO:
    * [openEO docs](https://docs.openeo.cloud/)
    * [Documentation on Data Products](https://docs.terrascope.be/#/DataProducts/DataProducts)
* [EGI Cloud Docs](https://docs.egi.eu/users/cloud-compute/)

### HTC/HPC

* [SURF Spider Documentation](https://spiderdocs.readthedocs.io/)
* [EODC VSC Knowledgebase](https://support.eodc.eu/kb/faq.php?cid=9)
* [GRNET Aris Documentation](https://doc.aris.grnet.gr/)

## How to get support

There is an open discussion forum for C-SCALE on [GitHub](https://github.com/c-scale-community/discussions)

Each Use Case also has a dedicated space for collaboration in the C-SCALE GitHub Organisation:

* [Wetland Water Stresses](https://github.com/orgs/c-scale-community/projects/5)
* [LSDA](https://github.com/orgs/c-scale-community/projects/4)
* [HiSea](https://github.com/orgs/c-scale-community/projects/3)
* [RETURN](https://github.com/orgs/c-scale-community/projects/2)
* [Aquamonitor](https://github.com/orgs/c-scale-community/projects/1)

### Cloud

* GRNET: `c-scale-cloud<at>einfra.grnet.gr`
* EODC: `support<at>eodc.eu`
* CESNET: TBC
* INFN Bari: TBC
* [INCD Support](https://docs.egi.eu/support/)
* CloudFerro: `support<at>creodias.eu`
* [VITO Support](https://terrascope.be/en/forum)
* [EGI Support](https://docs.egi.eu/support/)

### HTC/HPC

* SURF
    * SRAM related issues: `sram-support<at>surf.nl`
    * Support is provided via [C-SCALE Github (1st line)](https://github.com/c-scale-community/discussions/discussions)
      and via [SURFsara Service Desk (2nd line)](https://servicedesk.surfsara.nl)
      (create a ticket here and specifically mention service Spider/Delena)
* EODC: `support<at>eodc.eu`
* GRNET: `support<at>hpc.grnet.gr`

## Software tools

TBD
