# Release Information

* **Version**: 1.2.0
* **Certified**: No
* **Authored By**: Parag Khatavkar & Mahdi Naili (Fortinet CSE)
* **Publisher**: Community
* **Compatible Version**: FortiSOAR v7.2.0 and above
* [Release Notes](./release_notes.md)
# Overview

Solution Pack has the below use cases:
- **Indicators extraction from files**: examines Advisories sent by various organizations via email with attachments in PDF, Excel, CSV, and other formats. `File Metadata` and `File Content` is added to the record's Description. It sends a report with the count of IPs, Domain Name, Hashes, URLs, and so on if they are discovered via Email
    - Relevant playbooks:
        - Extract and Process Text From Indicator File
        - Extract and Process Text From Attachment File

- **Indicators hunting on SIEM**: Indicators from any attachment file are extracted, sha1 and sha246 hash codes are resolved to md5 via AlienVault OTX and VIrusTotal integrations. A search for each indicator value is triggered on SIEM (Qradar as of 1.2) and if a matching event(s) exists the indicator description is updated and matching events are attached.

![](./docs/res/Description.png)


# Next Steps

| [Installation](docs/setup.md#installation) | [Configuration](docs/setup.md#configuration) | [Usage](docs/usage.md) | [Contents](docs/contents.md) |
|--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
