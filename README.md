# Creating VPN Endpoints on OpenStack

These templates and instructions are provided to help you create a VM in your OpenStack project, 
performing the task of a VPN endpoint, allowing secure connections to be made to other projects, 
vCloud Director VDCs, or back to your own infrastructure in-house.

For instructions on how to use the OpenStack HEAT template to deploy a VPN endpoint, please see
the [documentation in the wiki](https://github.com/UKCloud/vpn-on-openstack/wiki).

This repository contains the following:
* pfsense.yaml
  * A HEAT template to deploy all the resources needed for an IPsec VPN Endpoints
* properties.yaml
  * The HEAT parameters used with the pfsense.yaml template
* infrastructure.yaml
  * A sample HEAT template to deploy all the pre-requisit infrastructure used by the pfsense.yaml template
* vshield-configuration.yaml
  * A sample configuration to setup a vShield Edge as an IPsec endpoint on a VDC.
* images
  * Various screenshots and diagrams used by the wiki documentation.

License and Authors
-------------------
Authors:
  * Rob Coward (rcoward@ukcloud.com)

Copyright 2016 UKCloud

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.