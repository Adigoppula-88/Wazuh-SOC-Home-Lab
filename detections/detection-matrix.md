\# Detection Matrix



| Detection | Endpoint | Event | Wazuh Rule | What it shows |

|---|---|---:|---:|---|

| Failed Logon | `SOC\_AD` | 4625 | 60122 | Authentication failure detection and investigation |

| Account Creation | `SOC\_AD` | 4720 | 60109 | Active Directory account-change monitoring |



\## Supporting Controls



\- \*\*Sysmon\*\* — installed on `SOC\_AD` and `SOC\_WS1` for detailed Windows telemetry.

\- \*\*CrowdSec\*\* — installed on `SOC\_AD` and `SOC\_WS1` for endpoint security.

\- \*\*FIM\*\* — realtime file-change monitoring validated on `SOC\_WS1`.

\- \*\*pfSense\*\* — firewall, routing, and network segmentation.

