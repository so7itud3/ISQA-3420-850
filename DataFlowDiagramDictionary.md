##Data Flow Diagram Dictionary

NIST Package Vulnerability Data: This is a datastore that can process software packages and compare them to known vulnerabilities. Requests to this datastore return a vulnerability list.

Scan for Licenses: This process checks FOSSology for software package license information. It returns known license information.

Manage Software Package for License and Vulnerability Scanning: This process receives a software package and gets known vulnerabilities and license information. Results are stored in the Software Package License & Vulnerability Datastore.

Software Package License & Vulnerability Datastore: This is a datastore that stores the results for software package license and vulnerability information.

Software Package License & Vulnerability Policy Datastore: This is a datastore that stores acceptable use policies set by corporate management.

Manager: Actor responsible for setting acceptable use for open source software package. Can submit new policies, retrieve policies, and retrieve license and vulnerability information.

Developer: Actor responsible for submitting software packages to be scanned for license and vulnerability information. Can submit packages, retrieve policies, and retrieve license and vulnerability information.
