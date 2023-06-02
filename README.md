## BRKATO-1557: Automating Detection & Response Outcomes using Cisco XDR <br><sub>.. and how CX Automation Services can help!</sub><div> <br> </div>

[About Cisco Live](https://www.ciscolive.com/global.html) | [**Link to Session Presentation**]() | [**Link to Session Recording**]() 

**Scenario:** Your organization has several remote employees who are using their personal devices to access sensitive company data. One of the employee's laptops gets infected with ransomware that attempts to establish command & control communication before initiating data encryption.

Cisco XDR gathers the event information generated by Cisco Umbrella, including the nature of the threat (C&C, High Severity), the associated domain/s (ex: monsteradds.at), and details about the affected employee's device. A response workflow in XDR Automate is automatically triggered. 

In this repository:
1. [XDR - Create Critical Incident](https://github.com/ciscomanagedservices/ciscolive-xdr-automate/tree/main/XDR-CreateCriticalIncident__definition_workflow_024XNSSKYEB9B7dKljmDwc4Nn6QKfos2ioh): Simulates a mock Command & Control detection incident created by Umbrella. This is for non-production use only.
2. [XDR - Command & Control Response](https://github.com/ciscomanagedservices/ciscolive-xdr-automate/tree/main/XDR-CommandAndControlResponse__definition_workflow_025W2TC4F9AOH1RGNNrFqURl7VGcdKBKRZR): This workflow is triggered automatically in response to a Command & Control event picked up by Cisco Umbrella that creates an incident in Cisco XDR. This is for non-production use only.

Please note that workflow content in this repository will not be kept up to date with new code releases/patches. If you're a Cisco Live attendee, you may create an issue on this repository or reach out to us via email for queries and/or feedback.

Oh and, while you're here, you may want to check out [some of our other content](https://github.com/ciscomanagedservices) as well 🚀 

---

Contributors:

1. Aman Sardana (amasarda@cisco.com)
2. Scott Dozier (scdozier@cisco.com)

Cisco CX Automation, June 2023
