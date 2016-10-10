## Use Case 1
Title: Determine License and Vulnerability Information

Primary Actor: Manager

Goal in Context: The manager is able to determine license and vulnerability information from the provided project information

Stakeholders:
•	Manager – To receive clear and relevant project information
•	Developer – To provide the relevant file/package level information
•	Project Owner: To clearly understand manager decisions to green/red light a project

Preconditions:
•	Relevant file/package information is in the SPDX database
•	Proper project information has been provided

Main Success Scenario: Manager receives accurate license and vulnerability information for the requested project packages

Failed End Conditions: Manager receives inaccurate or invalid license and vulnerability information for the requested project packages

Trigger: Manager selects a project and sends a request for that project to the system to retrieve license and vulnerability information for that project
