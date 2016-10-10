##Data Flow Diagram Dictionary

NIST Package Vulnerability Data: This is a datastore that can process software packages and compare them to known vulnerabilities. Requests to this datastore return a vulnerability list

Scan for Licenses: This process checks FOSSology for software package license information. It returns known license information.

Manage Software Package for License and Vulnerability Scanning: This process receives a software package and gets known vulnerabilities and license information. Results are stored in the Software Package License & Vulnerability Datastore
