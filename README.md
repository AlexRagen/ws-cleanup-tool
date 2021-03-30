![Logo](https://whitesource-resources.s3.amazonaws.com/ws-sig-images/Whitesource_Logo_178x44.png)  

[![License](https://img.shields.io/badge/License-Apache%202.0-yellowgreen.svg)](https://opensource.org/licenses/Apache-2.0)
[![GitHub release](https://img.shields.io/github/release/whitesource-ps/wss-template.svg)](https://github.com/whitesource-ps/wss-template/releases/latest)  
# WhiteSource Projects Cleanup Tool
### Tool to archive projects from White Source Application.
* The tool generates reports for each project in **WhiteSource** Organization which its last Update Date is more than the designated Days to Keep (default 60)
* The reports are saved in a designated location in form of: _[ReportsDir]/[PRODUCT NAME]/[PROJECT NAME]/[REPORT NAME]_  
* **DryRun** flag  can be used to review the outcome of a run
* **SkipReportGeneration** Can be used to delete projects without archiving

## Supported Operating Systems
- **Linux (Bash):**	CentOS, Debian, Ubuntu, RedHat
- **Windows (PowerShell):**	10, 2012, 2016

## Pre-requisites
* Python 3.6+

## Installation
1. Download and unzip **ws-projects-cleanup.zip** 
1. Edit file **param.config** with the appropriate parameters

## Execution
####It is recommended to schedule the cleanup as overnight task
1. `python projects_cleanup.py`

OR
1. `python projects_cleanup.py <CONFIG_FILE>` 
  
 