| [Home](../README.md) |
|--------------------------------------------|

# Contents

The **File Content Extraction** solution pack contains the following resources.

## Connectors

|**Name**|**Description**|
| :- | :- |
| Exchange | The Exchange connector provides a robust, platform-independent, and simple interface for communicating with Microsoft Exchange 2007-2016 Server or Office 365 using Exchange Web Services (EWS). |
| File Content Extraction | File Content Extraction extracts content, metadata, and artefacts from over 1500 file types, including MS Office, PDF, and others. |
| IBM QRadar | IBM QRadar is an enterprise security information and event management (SIEM) product. Fortinet FortiSOSR connector for IBM QRadar allows user to invoke QRadar API, perform Ariel Queries and operations like Get Offense,related events,update and close offenses. |
| AlienVault-OTX | AlienVault-OTX is an open source of Indicators of Compromise (IOCs) supported by the community.This connector provides actions Get IP Reputation, Create Pulse, Get Domain Reputation, etc |
| VirusTotal | VirusTotal provides a service that analyzes suspicious files and URLs and facilitates the quick detection of viruses, worms, trojans, and all kinds of malware. This connector facilitates automated operations such as scanning and analyzing suspicious files and URLs and retrieving reports from VirusTotal for files, IP addresses, and domains. | 
 

## Global Variable

|**Name**|**Description**|
| :- | :- |
| Demo_mode | This contains the value as `true` or `false` to execute mock output |
| Excludelist_IPs | This contains the list of IPs to be excluded. |
| Excludelist_URLs | This contains the list of URLs to be excluded. |
| Excludelist_Domains | This contains the list of Domains to be excluded. |
| Server_fqhn | This contain the Hostname of Machine. |

## Playbook Collection

|Playbook Collection Name |
| :- |
| 02 - Use Case - File Content Extraction |

**Playbook Name**|**Description**|
| :- | :- |
| Extract and Process Text From Indicator File | Enriches Attachment with extracted text, indicators and Meta data |
| Extract and Process Text From Attachment File | Enriches Indicator with extracted text, indicators and Meta data |
| Extract and Hunt Indicators on SIEM | Extracts indicators from a file and checks for any match on SIEM Events |
| > Hunt Indicators on Qradar | Hunt indicator value on Qradar for the past X Minutes |
| > Lookup Hash Codes Details | Get Hash Code Details and create Indicator for MD5, SH1, SH256 |

>**Warning:** We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.
