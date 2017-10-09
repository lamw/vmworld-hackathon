# VMworld Hackathon

* [Highlights](#highlights)
* [Github Repos](#github-repos)
* [Resources](#resources)
* [Training Sessions](#training-sessions)
* [VMworld US Hackathon Pictures](#vmworld-us-hackathon-pictures)
* [VMworld EU Hackathon Pictures](#vmworld-us-hackathon-pictures)
* [Environment Details](#environment-details)
* [vSphere Web Client Customization](#vsphere-web-client-customization)

## Highlights

  * [VMworld Hackathon 2017 US/Europe Highlights](http://www.virtuallyghetto.com/2017/09/vmworld-hackathon-2017-highlights.html)

## Github Repos

**VMworld US 2017**

| Team # | Team Name                        | Github Repo                                                                   | One-Liner Description                                                                                                                                                                                                                                                                                               |
|--------|----------------------------------|-------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1      | Hacking hard, or hardly hacking? | https://github.com/davidseibel/vSphereSCG                                     | Our goal was to create a framework that would allow for scripted auditing and remediation of a vSphere environment against the Security Configuration Guide, or other user-defined standard                                                                                                                         |
| 2      | Ohai Chefs!                      | https://github.com/jjasghar/vra-iaas-cookbook                                 | A way to repeatably create IAAS machines for Windows 2k12 for vRA                                                                                                                                                                                                                                                   |
| 3      | Defenders of the Keystore        | https://github.com/TheNetworkNerd/VMworldHackathon2017_DefendersOfTheKeystore | Our goal was to encrypt two VMs using Hytrust as the KMS, which involves deploying a two-node Hytrust cluster, registering and configuring the KMS nodes with vCenter, creating VMs to encrypt, and actually turning on encryption for the VMs in question so a vSphere admin could just start using VM Encryption. |
| 4      | SABUtage                         | https://github.com/tlindsay42/VMworldHackathon2017_SABUtage                   | Our goal was to use PowerCLI to automate an end-to-end setup of a vSAN stretched cluster. Right now, there are a bunch of manual steps involved around HA, DRS, affinity groups, etc. The objective will be to have this automated (and learn something along the way)                                              |
| 5      | The Humble Brackets              | https://github.com/kovarus/vmworld-us-hackathon-2017                          | Enhance Amazon Echo integration with VMware products by enabling more capabilities of the vrealize-pysdk that Rusell Pope created. Also create a web front end that will show what requests are being made to the echo, with details about the request.                                                             |
| 6      | Team #Migrate2VCSA               | https://github.com/kmruddy/vcenter_migration                                  | Initial goal is to solve the problem of horizontal migrations when users would like to move from a Windows based vCenter to the VCSA. Long term goal, build a tool which can take any given vCenter environment, then replicate the settings and configuration to any other vCenter.                                |
| 7      | See My Vest                      | https://github.com/brianbunke/VesterHackathon2017                             | NO DETAILS FROM TEAM                                                                                                                                                                                                                                                                                                |
| 8      | Need for Speed                   | https://github.com/alanrenouf/vCheck-vSphere/pull/580                         | fixed some issues in vCheck (main + plugins) - tried to introduce parallelisation, but were unable to test the solution                                                                                                                                                                                             |
| 9      | SweaterVester                    | https://github.com/BelayTechnologies/XesterUI                                 | add functionality allowing a collection of Vester tests run on different vCenters be combined and displayed in a User-Interface as a single System.                                                                                                                                                                 |
| 10     | Wavefront                        | NO DETAILS FROM TEAM                                                          | NO DETAILS FROM TEAM                                                                                                                                                                                                                                                                                                |
| 11     | Ops Ninjas                       | https://github.com/prydin/vrops-drift                                         | The Drifter uses vROps API to set a baseline for resource configuration; combine this with alert on resource config change, find offender in Log Insight query, kick off workflow to isolate offender via NSX                                                                                                       |
| 12     | Team vXTreme                     | https://github.com/ThepHuck/Hackathon                                         | Created app deployment automation to allow for 0-downtime deployments using only NSX. App to demonstrated virtually no downtime with realtime connection logging.                                                                                                                                                   |
| 13     | Team Quebec                      | NO DETAILS FROM TEAM                                                          | NO DETAILS FROM TEAM                                                                                                                                                                                                                                                                                                |
| 14     | Team Something Cool              | NO DETAILS FROM TEAM                                                          | NO DETAILS FROM TEAM                                                                                                                                                                                                                                                                                                |
| 15     | CloudyOps                        | NO DETAILS FROM TEAM                                                          | NO DETAILS FROM TEAM                                                                                                                                                                                                                                                                                                |

**VMworld Europe 2017**

| Team # | Team Name                              | Github Repo                                                 | Description                                                                                                                                               |
|--------|----------------------------------------|-------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1      | Checky mcViewCheck                     | https://github.com/vCheckReport/vCheck-HorizonView          | Expanding the well known vCheck with plugins to check VMware Horizon                                                                                      |
| 2      | Need for Speed                         | https://github.com/alanrenouf/vCheck-vSphere/pull/580       | Fixed some issues in vCheck (main + plugins) - added internationalization                                                                                 |
| 3      | Join the Clarity Side                  | https://github.com/vmworld-hackathon-2017/barcelona-team-3  | Debian packer template for the h5pxe which is a Python/Django app for basic VMware ESXi kickstarting through DHCP/PXE, and tentative HTML5 Clarity UI     |
| 4      | Automation for All                     | https://github.com/pdellaert/automation-for-all             | Develop Ansible roles that could deploy (and destroy) the different components of VIC, including more flexibility in the amount of VCH’s you could set up |
| 5      | PowerTheVSAN                           | https://github.com/mitsumaui/PowerTheVSAN                   | PowerCLI cmdlets to help with vSAN Day 2 Ops                                                                                                              |
| 6      | Security for Fun and Beer              | NO DETAILS FROM TEAM                                        | NO DETAILS FROM TEAM                                                                                                                                      |
| 7      | One Pod To Rule Them All               | https://github.com/sammcgeown/Pod-Deploy                    | NO DETAILS FROM TEAM                                                                                                                                      |
| 8      | Physical World Monitoring and Alerting | https://github.com/AnykeyNL/vDefCon                         | Make integration with physical world devices to monitor and alert about a VMware Environments.                                                            |
| 9      | Perspectives in Clarity                | https://github.com/burkeazbill/perspectives-on-clarity-seed | An attempt to get a Clarity based front-end on vRealize Orchestrator in an effort to restore the old Perspectives Webview functionality.                  |
| 10     | $null                                  | NO DETAILS FROM TEAM                                        | NO DETAILS FROM TEAM                                                                                                                                      |

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
  * Slide: [http://bit.ly/vmworld-clarity](http://bit.ly/vmworld-clarity)
  * Github: [http://git.io/vmworld-clarity](http://git.io/vmworld-clarity)
* **Integrating VMware API’s and Amazon Echo (Alexa) [VMTN6721U]**
  * Slide: [Hackathon-Training-VMTN6721U.pptx](https://github.com/lamw/vmworld-hackathon/raw/master/Training/Hackathon-Training-VMTN6721U.pptx)
  * Github: [https://github.com/codyde/Hackathon-Training](https://github.com/codyde/Hackathon-Training)
* **Open Source Projects for Enterprise Cloud Native Applications [VMTN6718U]**
  * Slide: [Hackathon-Training-VMTN6718U.pdf](https://github.com/lamw/vmworld-hackathon/raw/master/Training/Hackathon-Training-VMTN6718U.pdf)
* **Getting started with the vSphere Automation SDK for Python [VMTN6720U]**
  * Slide: [Hackathon-Training-VMTN6720U.pptx](https://github.com/lamw/vmworld-hackathon/raw/master/Training/Hackathon-Training-VMTN6720U.pptx)
  * Github: [https://vmware.github.io/vsphere-automation-sdk-python/](https://vmware.github.io/vsphere-automation-sdk-python/)

## VMworld US Hackathon Pictures

* [https://github.com/lamw/vmworld-hackathon/tree/master/2017-USA-Pictures](https://github.com/lamw/vmworld-hackathon/tree/master/2017-USA-Pictures)

## VMworld EU Hackathon Pictures

* [https://github.com/lamw/vmworld-hackathon/tree/master/2017-BCN-Pictures](https://github.com/lamw/vmworld-hackathon/tree/master/2017-BCN-Pictures)

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

## vSphere Web Client Customization

Download the [websso.war](vSphere-Web-Client-2017-Customization/websso.war) package copy that to the vCenter Server Appliance (VCSA) located under **/usr/lib/vmware-sso/vmware-sts/webapps**. If you wish to create your own customization based on this theme, you can following this blog post [here](http://www.virtuallyghetto.com/2017/09/vmworld-hackathon-vsphere-client-login-ui-theme.html)

**Note:** The websso.war has been created specifically for a vSphere 6.5 Update 1 environment. Simply copying this to earlier version of vSphere probably will not work and you will need to use follow this blog post [here](http://www.virtuallyghetto.com/2017/09/vmworld-hackathon-vsphere-client-login-ui-theme.html) to create the customization for earlier versions of vSphere.

![](vSphere-Web-Client-2017-Customization/VMworldHackathon-WebClientTheme.gif)