# AMA  (Application Modernization Accelerator) Lab

For this, lets us reuse most of things from the MoRE lab.

## 1. Download Setup and Demo Guides

1. Already you might have downloaded the More Setup Guide and Demo Guide from the techzone url https://techzone.ibm.com/collection/mo-re--ama-demos-and-environment-2q25-release/resources

If not, just Download the `Setup Guide` doc from the tile `MoRE 1.0.0.1 demo environment reservations and setup guide`

## 2. Reserve Techzone Instance

1. If you have not reserved the MoRE demo instance, reserve the MoRE Demo instance in the Techzone by using the url https://techzone.ibm.com/collection/mo-re--ama-demos-and-environment-2q25-release/environments

    Note: You can use the `Setup Guide` document `Setup Guide - MoRE Demo Environment v4.docx` that you downloaded in the previous step.

    #### Steps

    Here are the steps involved in this section.

    1. Reserve demo environment in Techzone
    2. Access demo environment through noVNC
    3. Tips for working in the Demo environment
    4. Start the WebSphere environment 

## 3. Setup Demo Environment

1. Execute all the steps mentioned in the downloaded `Setup Guide` document `Setup Guide - MoRE Demo Environment v4.docx`

    Note: you might have already completed few steps as part of the previous section (Reserve Techzone Instance)

    #### Steps

    Here are the steps involved in this section.

    1. Access demo environment through noVNC
    2. Tips for working in the Demo environment
    3. Start the WebSphere environment

## 4. Start AMA in the demo environment 

1. Change to the directory where AMA is installed

```
 cd ~/application-modernization-accelerator-local-4.3.0/
 scripts/startLocal.sh 
```

3. Wait until AMA has started successfully, and the URL is displayed.

```
Configuring Application Modernization Accelerator .........................................................
Status
------------------------------------------------------------------------------------------------------
Application Modernization Accelerator 4.3.0 is available for use at the following URL> https://rhel9-base.gym.lan:3001
```

3. Open the URL `https://rhel9-base.gym.lan:3001` inside the remote desktop browser.


## 4. Run the AMA Demo Steps

To run the AMA Demo, the steps are given in the TechZone URL https://techzone.ibm.com/collection/mo-re--ama-demos-and-environment-2q25-release/resources as a tile `AMA - AMA Dev Tools - MoRE End to end lab`

1. You can start the Demo from this step from here.  https://github.com/LarsBesselmann/MoRE_WhereAMI_Lab?tab=readme-ov-file#user-content-run-the-ama-data-collector-to-scan-the-environment

2. You can stop the demo from this step 
https://github.com/LarsBesselmann/MoRE_WhereAMI_Lab?tab=readme-ov-file#user-content-use-the-ama-dev-tools-to-apply-automated-fixes

or at this step.

https://github.com/LarsBesselmann/MoRE_WhereAMI_Lab?tab=readme-ov-file#user-content-set-up-the-managed-liberty-cluster-and-deploy-the-modernized-whereami-application


## 5. Note

If you have challenges in setting up the environment you can install the traial version in your local system. Here are the links.

1. Installing AMA in local : https://github.com/GandhiCloudLab/ibm-websphere-ama/tree/main/01-ama-local-install

2. AMA in detail : https://github.com/GandhiCloudLab/ibm-websphere-ama/tree/main/02-ama-in-detail


