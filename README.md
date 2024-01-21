<h1>Security Map SIEM - Azure Sentinel Setup with Cloud-Based Honeypot</h1>

<h2>Description</h2>
<b>This project focuses on deploying Azure Sentinel, configuring a cloud-based honeypot virtual machine, and visualizing global cyber threats on a map.
</b>
<br />
<br />

<h2 align="center">World map depicting incoming attacks worldwide, using custom logs</h2>

<p align="center">
<img src="https://i.imgur.com/wjY1wUY.jpg" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

Follow this step-by-step process to set up the Security Map SIEM project, emphasizing the integration of Azure Sentinel with a cloud-based honeypot. The objective is to offer a practical experience in deploying a Security Information and Event Management (SIEM) system using Microsoft's Azure Sentinel, with a special emphasis on visualizing global cyber threats on a map.
<br />
<br />
<b>1. Azure Subscription Creation:</b> Begin by creating a free Azure subscription, which includes $200 worth of credits. This subscription is essential for accessing Azure services.
<br />
<br />
<b>2. Virtual Machine Setup:</b> Create a honeypot virtual machine (VM) in Azure. Optimize exposure by disabling external and Windows firewalls to attract potential attackers.
<br />
<br />
<b>3. Log Repository - Log Analytics Workspace:</b> Establish a Log Analytics Workspace in Azure to serve as a centralized log repository. This workspace will ingest logs from the honeypot VM.
<br />
<br />
<b>4. Azure Sentinel Configuration:</b> Set up Azure Sentinel within Azure. This cloud-native SIEM solution will be the cornerstone for visualizing attacker data on a map based on geographical information.
<br />
<br />
<b>5. PowerShell Integration:</b> Integrate PowerShell into the lab to extract IP addresses from Windows logs. This involves sending IP addresses to a third-party API to obtain geographical data, enriching custom logs for deeper analysis.
<br />
<br />
<b>6. Key Features and Alerts:</b> While triggers and alerts are typical SIEM features, this lab focuses on extracting failed log-on data and visualizing it on a world map.
<br />
<br />
<b>7. Conclusion:</b> Embark on the Security Map SIEM journey to enhance your cybersecurity skills. Happy learning!
<br />
<br />

<h4>Languages and Utilities Used:</h4>

- <b>PowerShell:</b> Retrieve Windows Event Viewer logs containing unsuccessful RDP login attempts.
- <b>ipgeolocation.io:</b> Utilize the IP Address to Geolocation API.

<h2 align="center">Logs with customized information, including geospatial data</h2>

<p align="center">
<img src="https://i.imgur.com/r8TaOV3.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2 align="center">IP Geolocation API</h2>

<p align="center">
<img src="https://i.imgur.com/3C4f1uE.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
