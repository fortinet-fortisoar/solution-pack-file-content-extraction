| [Home](https://github.com/fortinet-fortisoar/solution-pack-file-content-extraction/blob/release/1.1.0/README.md) |
|--------------------------------------------|

# Contents

The **File Content Extraction** solution pack contains the following resources.

## Connectors

|**Name**|**Description**|
| :- | :- |
| Exchange | The Exchange connector provides a robust, platform-independent, and simple interface for communicating with Microsoft Exchange 2007-2016 Server or Office 365 using Exchange Web Services (EWS). |
| File Content Extraction | File Content Extraction extracts content, metadata, and artefacts from over 1500 file types, including MS Office, PDF, and others. |

## Global Variable

|**Name**|**Description**|
| :- | :- |
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

>**Warning:** We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.
