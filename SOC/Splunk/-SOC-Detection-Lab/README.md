# Splunk SOC & Detection Engineering Lab
Hands-on SOC lab focused on SIEM monitoring, Windows endpoint telemetry, detection engineering, threat hunting, and incident investigation.

## Architecture

Kali Linux
    ↓
Windows 11 + Sysmon
    ↓
Splunk Universal Forwarder
    ↓
Splunk Enterprise
    ↓
Detection & Investigation

## Technologies

Splunk Enterprise • Splunk Universal Forwarder • Sysmon • Windows 11 • Kali Linux • VMware • SPL • MITRE ATT&CK

## Completed

* Built an isolated Windows and Kali Linux security lab using VMware.
* Deployed and configured Microsoft Sysmon for detailed Windows endpoint telemetry.
* Configured Splunk Universal Forwarder to collect and forward Sysmon events.
* Deployed Splunk Enterprise as the centralized SIEM and configured event receiving.
* Established a working Windows-to-Splunk security monitoring pipeline.
* Ingested and analyzed 6,000+ Sysmon events in Splunk.
* Extracted structured fields from XML-based Windows event data.
* Analyzed Sysmon Event IDs, including process creation activity, for security investigations.

## Next Development

* Build and validate Splunk detection rules for suspicious activity.
* Perform controlled attack simulations and investigate generated telemetry.
* Develop threat-hunting queries and investigation workflows.
* Map confirmed detections and techniques to MITRE ATT&CK.
* Build SOC dashboards for monitoring and investigation.
* Add Python-based security automation and enrichment.
* Extend the lab with network and cloud security telemetry.
