# JIRA Web Services Connector
This is a template to automatically create incident tickets in JIRA with Basic auth, from OpCon

# Disclaimer
No Support and No Warranty are provided by SMA Technologies for this project and related material. The use of this project's files is on your own risk.

SMA Technologies assumes no liability for damage caused by the usage of any of the files offered here via this Github repository.

# Prerequisites
- OpCon V19.1
- Web Services Connector V 20.0.3 
- In Jira Create an API token see documentation
- Create two new Global Properties : 
  - [[Jira-url]] : your JIRA API url https://yourapp.atlassian.net/rest/api/3
  - [[Jira-Auth]] : Value useremail:api_token (encode Base64) 

# Instructions
- Download the latest [release](https://github.com/SMATechnologies/jira-webservicestemplate/releases/tag/V1.0)  of .json file 
- Create your Opcon job Type = Windows, Sub-type = Web Services see documentation
- Import Template, choose your .json 
- Select step1 in your job, check the body json, and modify it if you need (OpCon Global Properties are supported)  

# License
Copyright 2019 SMA Technologies

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Contributing
We love contributions, please read our [Contribution Guide](CONTRIBUTING.md) to get started!

# Code of Conduct
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code-of-conduct.md)
SMA Technologies has adopted the [Contributor Covenant](CODE_OF_CONDUCT.md) as its Code of Conduct, and we expect project participants to adhere to it. Please read the [full text](CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.
