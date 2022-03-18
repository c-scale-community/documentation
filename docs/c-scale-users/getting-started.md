# Getting started

The aim of this section is to point you in the right direction to get started within the C-SCALE ecosystem.

These pages are targeted to users already onboarded onto the C-SCALE federation. If you want to become a user email `info<at>c-scale.eu`.

## Create a user account

Cloud and HTC/HPC services in C-SCALE currently require separate accounts. Please follow instructions below depending on the service that you are going to access.

### Cloud

The user account to access Cloud services is provided by EGI Check-In. Steps to create your Check-In account can be found in the [EGI Documentation](https://docs.egi.eu/users/check-in/signup/).

### HTC/HPC

The user account to access HTC/HPC services is provided by SURF Research Access Manager (or SRAM). Log into [SRAM](https://sram.surf.nl/) with your preferred Identity Provider and upload your public SSH key to your [profile page](https://sram.surf.nl/profile). 

## Join user groups

After creating your user account the next step is to join the relevant user group. So far we have created a user group per Use Case. Therefore, search for the given name of your Use Case and join the appropriate group.

### Cloud

The information about user groups for Cloud services is available in [EGI Operations Portal](https://operations-portal.egi.eu/vo/a/list). Search for "C-SCALE" to find all the available groups:

* [Aquamonitor](https://operations-portal.egi.eu/vo/view/voname/aquamonitor.c-scale.eu)
* [HiSea](https://operations-portal.egi.eu/vo/view/voname/hisea.c-scale.eu)
* [LSDA](https://operations-portal.egi.eu/vo/view/voname/HighResLandSurf.c-scale.eu)
* [Return](https://operations-portal.egi.eu/vo/view/voname/return.c-scale.eu)
* [WaterWatch](https://operations-portal.egi.eu/vo/view/voname/waterwatch.c-scale.eu)
* Wetland Water Stresses (pending) 

User groups in the Cloud federation are also known as [Virtual organisations](https://confluence.egi.eu/display/EGIG/Virtual+organisation) (or VOs), and the links above are called VO ID Cards.

Users will have to visit the **enrolment URL** to request access. Each petition needs to be approved by the corresponding VO manager. The enrolment URL and the VO manager for each user group can be found in each VO Card.

### HTC/HPC

The information about user groups for HTC/HPC services is available in [SRAM Collaborative Organisation (or COs)](https://sram.surf.nl/home/collaborations)

So far we have only created a single user group in SRAM for the HiSEA Use Case:

* [HiSea](https://sram.surf.nl/registration?collaboration=9b0a6184-326e-44d8-bc1d-903193b11f2b)

The link above is the **Join Request URL** that users will have to visit to request access. Each petition needs to be approved by the corresponding CO Admin. 

## Access to services

### Cloud

Below is the list of OpenStack Horizon dashboards participating in the Cloud federation in C-SCALE:

* [GRNET OpenStack](https://ui.cloud.grnet.gr/)
* [EODC OpenStack](https://launcher.eodc.eu/)
* [CESNET OpenStack](https://dashboard.cloud.muni.cz/)
* [INFN Bari OpenStack](https://cloud.recas.ba.infn.it/)
* [INCD OpenStack](https://stratus.ncg.ingrid.pt/)
* [CloudFerro OpenStack](https://cf2.cloudferro.com/)

When logging into the Horizon dashboard of OpenStack sites select either **OpenID Connect** or **EGI Check-In** in the dropdown menu. Then use your EGI Check-In credentials.

#### INDIGO PaaS Orchestrator

Cloud resources can also be deployed with the [INDIGO PaaS Orchestrator](https://indigo-paas.cloud.ba.infn.it/). Check out the [status dashboard](https://indigo-paas-status.cloud.ba.infn.it/) in case of issues.

If it is your first time using the service please send the following details:
* OpenStack cloud keystone endpoint
* Name of OpenStack project
* Name of the Virtual Organization
* The allocated quota (cores, RAM, storage)

to `indigo-paas-support<at>lists.infn.it` to configure the service for your Use Case.

### HTC/HPC

Here are the instructions on how to access the HTC/HPC federation in C-SCALE:

* SURF Delena:
    * Username: `sram-[CO short name]-[SRAM username]`
    * Connect via: `ssh -YC sram-[CO short name]-[SRAM username]@delena.surfsara.nl`
* [EODC VSC](https://support.eodc.eu/kb/faq.php?id=18)
* [GRNET Aris](https://doc.aris.grnet.gr/login/)

### openEO

Access to openEO is explained in the [openEO documentation](https://docs.terrascope.be/#/Developers/WebServices/OpenEO/OpenEO?id=logging-in).

## Providers documentation

Check the relevant section below to access the documentation for each provider in C-SCALE.

### Cloud

Links to documentation on each Cloud provider:

* [GRNET OpenStack Documentation](https://help.cloud.grnet.gr/)
* [EODC Openstack Knowledgebase](https://support.eodc.eu/kb/faq.php?cid=6)
* INCD
    * [Tutorial Openstack Dashboard](https://docs.google.com/presentation/d/1yERFe9v5xupjPJcZAnVdI1kmKXg4nlb3MlTZIYviVHQ/)
    * [Tutorial Openstack Command-Line Interface](https://lip-computing.github.io/tutorials/openstack-cli/oscli.html)
* [CESNET](https://docs.cloud.muni.cz/)
* [INFN Bari](https://www.recas-bari.it/index.php/en/recas-bari-users/guides-and-handbooks)
* [CloudFerro FAQ](https://creodias.eu/faq)

#### INDIGO Paas Orchestator

See the [INDIGO PaaS Orchestrator guides](https://github.com/indigo-dc/orchestrator#guides).

### HTC/HPC

Links to documentation for HTC/HPC providers:

* [SURF Spider Documentation](https://spiderdocs.readthedocs.io/)
* [EODC VSC Knowledgebase](https://support.eodc.eu/kb/faq.php?cid=9)
* [GRNET Aris Documentation](https://doc.aris.grnet.gr/)

### openEO

See documentation about openEO in the following links:
* [openEO docs](https://docs.openeo.cloud/)
* [Documentation on Data Products](https://docs.terrascope.be/#/DataProducts/DataProducts)

## How to get support

There is an forum for C-SCALE on [GitHub](https://github.com/c-scale-community/discussions).

Each Use Case also has a dedicated space for collaboration in the C-SCALE GitHub Organisation:

* [Aquamonitor](https://github.com/orgs/c-scale-community/projects/1)
* [HiSea](https://github.com/orgs/c-scale-community/projects/3)
* [LSDA](https://github.com/orgs/c-scale-community/projects/4)
* [RETURN](https://github.com/orgs/c-scale-community/projects/2)
* [WaterWatch](https://github.com/orgs/c-scale-community/projects/6)
* [Wetland Water Stresses](https://github.com/orgs/c-scale-community/projects/5)

At the moment Use Cases are working on private GitHub repositories and you need to request access providing your GitHub username via the forum.

### Cloud

Support for each Cloud provider is provided below:

* CloudFerro: `support<at>creodias.eu`
* EODC: `support<at>eodc.eu`
* GRNET: `c-scale-cloud<at>einfra.grnet.gr`

The following Cloud providers offer support via [EGI Support](https://docs.egi.eu/support/):
* CESNET
* INFN Bari
* INCD (also known as NCG-INGRID-PT)

If you are using the [EGI Helpdesk](https://ggus.eu/index.php?mode=ticket_submit) choose the correct Cloud provider in the **Notify Site** dropdown menu on the bottom left.

### HTC/HPC

See below how to request request support for the different HTC/HPC providers in C-SCALE:

* SURF
    * 1st line support is provided via [GitHub](https://github.com/c-scale-community/discussions/discussions)
    * 2nd line support is provided via [SURFsara Service Desk](https://servicedesk.surfsara.nl). Please create a ticket specifying the service **Delena**.

* EODC: `support<at>eodc.eu`
* GRNET: `support<at>hpc.grnet.gr`

### openEO

Request support for openEO in the [Terrascope forum](https://terrascope.be/en/forum).

### Support for authentication or authorization

In case of issues with:
* EGI Check-In: use the [EGI Helpdesk](https://ggus.eu/index.php?mode=ticket_submit) and select **Check-In (AAI)** in the **Support Unit** dropdown menu on the bottom right. 
* SRAM: email `sram-support<at>surf.nl`

## Software tools

TBD

