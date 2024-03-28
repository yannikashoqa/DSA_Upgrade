# DSA_Upgrade


AUTHOR		: Yanni Kashoqa

TITLE		: Agent Software Upgrade via SOAP APIs 

DESCRIPTION	: This Powershell script will initiate a software upgrade of any agent by calling the Agent Upgrade function on the Deep Security Manager..  Script can run on any Windows system that has PowerShell 5.1. 

REQUIRMENTS
  - Tested and working on:  Deep Security Manager Version 20.
  - PowerShell 5.1
  - knowledge of the Agent HostID.
  - Create a DS-Config.json with the following content
~~~~JSON
    {
        "MANAGER": "dsm.example.com",
        "PORT": "4119",
        "USER_NAME": "",
        "PASSWORD": ""
    }
~~~~
