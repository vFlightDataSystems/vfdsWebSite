---
nav_exclude: true
---

# Data Protection Policy
Last updated: February 17, 2026

This Data Protection Policy outlines how vfds.dev and the vEDST application protect and handle data in accordance with data protection principles.

# Data Protection Principles
Although vEDST does not collect personal data, we adhere to data protection principles in our design:

- Data Minimization: We do not collect any data beyond what is necessary for the application to function
- Purpose Limitation: Local settings are used solely to enhance your user experience
- Storage Limitation: No data is retained on external servers
- Transparency: We clearly communicate our data practices

# Types of Data
| Data Type	| Stored Location	| Transmitted Externally |
| --------- | --------------- | ---------------------  |
| Application settings | Local device only | No |
| VATSIM OAuth token | Local device / VATSIM | To VATSIM only |

# Third-Party Services
vEDST interfaces with the following third-party services:

## vNAS (Virtual National Airspace System)
- Integration with vNAS uses your existing CRC client connection
- No separate authentication or data collection by vEDST
- vNAS data handling is governed by VATSIM and vNAS policies
## NOAA Aviation Weather Center
- vEDST retrieves weather data via the NOAA API
- All API requests are made securely over HTTPS
- No personal data is included in API requests

# Security Measures
- **Local-Only Configuration**: Your settings never leave your device
- **Secure Connections**: All external API connections use HTTPS encryption
- **Open Source**: Our source code is publicly available for security review on GitHub

# Your Rights
Since vEDST does not collect personal data:
- **Access**: All your data is already on your local device and accessible to you
- **Deletion**: You can delete all local data by clearing your browser's local storage for the vEDST application

# GDPR and International Compliance
vEDST's data-minimal design inherently aligns with privacy regulations including GDPR. Since we do not collect, process, or store personal data on external systems, there is no personal data processing that would require a legal basis under GDPR.

# Changes to This Policy
We may update this Data Protection Policy from time to time. Changes will be posted on this page with an updated revision date. If we ever change our data practices to include data collection, we will provide clear notice and obtain any required consents.

# Contact
For questions about this Data Protection Policy or our data practices, please open an issue on our [GitHub repository](https://github.com/vFlightDataSystems/vfdsWebSite).
