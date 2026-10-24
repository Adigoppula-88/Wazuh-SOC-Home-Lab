# Detection Matrix

| Detection | Endpoint | Event | Wazuh Rule | What it shows |

|---|---|---:|---:|---|

| Failed Logon | `SOC_AD` | 4625 | 60122 | Authentication failure detection and investigation |

| Account Creation | `SOC_AD` | 4720 | 60109 | Active Directory account-change monitoring |

## Supporting Controls

- **Sysmon** — installed on `SOC_AD` and `SOC_WS1` for detailed Windows telemetry.

- **CrowdSec** — installed on `SOC_AD` and `SOC_WS1` for endpoint security.

- **FIM** — realtime file-change monitoring validated on `SOC_WS1`.

- **pfSense** — firewall, routing, and network segmentation.

