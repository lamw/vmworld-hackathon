# VMworld Hackathon

* [Resources](#resources)
* [Training Sessions](#training-sessions)
* [Environment Details](#environment-details)

## Resources

* VMworld US
  * [http://vmwa.re/hackathonus](http://vmwa.re/hackathonus) - Hackathon Details
  * [http://vmwa.re/hackathonussignup](http://vmwa.re/hackathonussignup) - Hacakathon Signup Sheet
  * [http://vmwa.re/hackathontraining](http://vmwa.re/hackathontraining) - Hackathon Training Session attendee prerequisite setup
  * [https://vmwarecode.slack.com/messages/#vmworld-hackathon](https://vmwarecode.slack.com/messages/#vmworld-hackathon) - Slack group

* VMworld Europe
  * [http://vmwa.re/hackathoneu](http://vmwa.re/hackathoneu) - Hackathon Details
  * [http://vmwa.re/hackathoneusignup](http://vmwa.re/hackathoneusignup) - Hacakathon Signup Sheet
  * [https://vmwarecode.slack.com/messages/#hackathon-europe](https://vmwarecode.slack.com/messages/#hackathon-europe) - Slack group

## Training Sessions

* **Getting started with Clarity [VMTN6719U]**
  * Video: [https://www.youtube.com/watch?v=8J4b_GqHN90](https://www.youtube.com/watch?v=8J4b_GqHN90)
  * Slide: [http://git.io/vmworld-clarity](http://git.io/vmworld-clarity)
  * Github: [http://bit.ly/vmworld-clarity](http://bit.ly/vmworld-clarity)
* **Integrating VMware API’s and Amazon Echo (Alexa) [VMTN6721U]**
  * Slide: [Hackathon-Training-VMTN6721U.pptx](https://github.com/lamw/vmworld-hackathon/raw/master/Training/Hackathon-Training-VMTN6721U.pptx)
  * Github: [https://github.com/codyde/Hackathon-Training](https://github.com/codyde/Hackathon-Training)
* **Open Source Projects for Enterprise Cloud Native Applications [VMTN6718U]**
  * Slide: [Hackathon-Training-VMTN6718U.pdf](https://github.com/lamw/vmworld-hackathon/raw/master/Training/Hackathon-Training-VMTN6718U.pdf)
* **Getting started with the vSphere Automation SDK for Python [VMTN6720U]**
  * Slide: [Hackathon-Training-VMTN6720U.pptx](https://github.com/lamw/vmworld-hackathon/raw/master/Training/Hackathon-Training-VMTN6720U.pptx)
  * Github: [https://vmware.github.io/vsphere-automation-sdk-python/](https://vmware.github.io/vsphere-automation-sdk-python/)

## Environment Details

Each team will be provided with a "vPod" environment that consists of the following:
  * 1 x vCenter Server Appliance (vSphere 6.5 Update 1)
  * 3 x Nested ESXi hosts (vSphere 6.5 Update 1)
  * vSAN will be the underlying storage (vSAN 6.6.1) within the Nested enviornment
  * VCSA is configured as 2 vCPU & 8GB memory
  * Each ESXi host will have 10GB memory
  * There is ~75GB of usable storage within the vPod (which can be expanded if required)
  * For additional product deployments, this will happen outside of the vPod (aka Layer1 on the phyiscal vSAN Cluster)
  * More details will be provided at the Hackathon

In addition, the following vSphere Content Library will be made available to all teams to use during the Hackathon to deploy additional solutions that are needed:

**Content Library Name:** Hackathon-Stuff

| **Content Library Item**                                | **Type** |
|-----------------------------------------------------------|------|
| HyTrust-KeyControl-4.0-11538                              | OVF  |
| VMware-NSX-Manager-6.3.2-5672532                          | OVF  |
| VMware-NSX-Manager-6.3.3-6276725                          | OVF  |
| VMware-VIMSetup-all-6.0.0-5326177.iso                     | ISO  |
| VMware-vR-Appliance-7.3.0.536-5610496                     | OVF  |
| VMware-vRO-Appliance-7.3.0.21553-5521409                  | OVF  |
| VMware-vRealize-Log-Insight-4.5.0-5654101                 | OVF  |
| VMware-vSAN-Witness-6.5.0.update01-5969303                | OVF  |
| Windows-Server-2012.iso                                   | ISO  |
| Windows-Server-2016-Template                              | OVF  |
| Windows-Server-2016.iso                                   | ISO  |
| photonOS-1.0                                              | OVF  |
| vRealize-Operations-Manager-Appliance-6.6.1.6163035       | OVF  |
| ubuntu-16.04.3-server-amd64.iso                           | ISO  |
| VMWare-vRealize-Network-Insight-3.4.0.1495004044-platform | OVF  |
| VMWare-vRealize-Network-Insight-3.4.0.1495004044-proxy    | OVF  |

**Content Library Name:** virtuallyGhetto-Nested-ESXi

| **Content Library Item**                     | **Type** |
|------------------------------------------|------|
| Nested_ESXi6.0u3_Appliance_Template_v1.0 | OVF  |
| Nested_ESXi6.5d_Appliance_Template_v1.0  | OVF  |
| Nested_ESXi6.5u1_Appliance_Template_v1.0 | OVF  |
