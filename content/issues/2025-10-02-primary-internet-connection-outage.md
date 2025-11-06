---
section: issue
title: Primary internet connection outage
date: 2025-09-26T00:09:10.561Z
resolved: true
draft: false
informational: false
pin: false
resolvedWhen: 2025-09-26T05:48:10.563Z
affected:
  - Tiehack
  - Moore
severity: down
---
*Issue Resolved, Vendor Investigation Suspended | 10/17 03:05pm Central* - After a support session with the vendor, further diagnostics need to be performed on site. Per the vendor, after recreating the issue and experiencing the issue with the wan2 connection loosing internet access after 90 minutes, the vendor should be contacted for more commands to be performed while directly connected via the management port on the FortiGate appliance.

*Issue Resolved, Vendor Investigating | 10/07 04:01pm Central* - The Technology Services continues to actively work with the vendor to determine the root cause of this downtime. After further review and escalation internally within vendor support, the vendor would like to conduct a technical support session to further investigate the root cause of the downtime and has been rescheduled for 10/17.

*Issue Resolved, Vendor Investigating | 10/01 02:54pm Central* - The Technology Services continues to actively work with the vendor to determine the root cause of this downtime. After further review and escalation internally within vendor support, the vendor would like to conduct a technical support session to further investigate the root cause of the downtime and has scheduled for 10/03.

*Issue Resolved, Vendor Investigating | 10/01 02:54pm Central* - The Technology Services continues to actively work with the vendor to determine the root cause of this downtime. After further review and escalation internally within vendor support, the vendor would like to conduct a technical support session to further investigate the root cause of the downtime. The Technology Services Department provided date and time windows as requested by the vendor.

*Issue Resolved, Vendor Investigating | 09/27 02:29pm Central* - The Technology Services continues to actively work with the vendor to determine the root cause of this downtime. We have provided supplemental information requested by the support engineer to aid FortiGate in their investigation of this issue.

*Issue Resolved, Vendor Investigating | 09/26 10:12am Central* - The Technology Services Department reports that the issue is now resolved. We are actively working with the vendor to determine the root cause of this downtime. Ticket 11145112 has been opened with FortiGate support and we are currently waiting on a response. Per our initial investigation of log files, due to the CGNAT configuration used by the backup internet connnection, the DHCP address renewal appears to have failed in which the FortiGate appliance could not recover and retry renewing the IP address lease. The Atelic Technology Services Department appreciates your patience and understanding while working through this service outage. If the issue is still occurring, please contact the Technology Services Department.

*Issue Resolved, Department Monitoring | 09/26 03:48am Central* - The FortiGate appliances at the Moore House and Tiehack in Aspen report that the Comcast Xfinity internet connection is back online at this time. Additionally, Cisco Meraki reports that all infrastructure has regained connectivity. The Technology Services Department will monitor the connection, and will begin conducting a complete investigation of the outage within twelve hours.

*Investigating | 09/25 11:24pm Central* - The Technology Services Department continues to investigate the issue affecting the primary internet connection at the Moore House and Tiehack in Aspen after reports from Cisco Meraki that all devices are offline. We have accessed our FortiGate and Cisco management portals and can confirm that the backup internet connection is no longer functioning as expected at this time, and have confirmed a loss of internet service with staff members on site. Once internet service has been restored, we will begin looking through logs to determine root-cause.The Atelic Technology Services Department has been able to validate this report. End user disruption is expected for this issue.

*Investigating | 09/25 10:30pm Central* - The Technology Services Department continues to investigate the issue affecting the primary internet connection at the Moore House and Tiehack in Aspen. We have accessed our FortiGate management portal and can confirm that the backup internet connection is functioning as expected at this time. We will continue to monitor to ensure the stability of our network. The Atelic Technology Services Department has been able to validate this report. End user disruption is not expected for this issue.

*Report Received | 09/25 10:09pm Central* - We are investigating a potential issue that might affect the uptime of one our of services. The FortiGate appliances at the Moore House and Tiehack in Aspen report that the Comcast Xfinity internet connection is offline at this time. We are sorry for any inconvenience this may cause you. The Technology Services Department will investigate this report shortly and will update this incident post once we have more information. Although Comcast Xfinity provides the primary internet service to the properties, Starlink provides backup internet service and thus no disruption of services is expected.