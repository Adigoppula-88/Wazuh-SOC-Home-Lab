# Endpoint Security Tooling

## SOC_AD

Role: Active Directory / Windows Server 2022 endpoint.

Validated services:

- Wazuh Agent — running
- Sysmon64 — running
- CrowdSec — running
- CrowdSec Windows Firewall Bouncer — running

## SOC_WS1

Role: Windows 10 Pro workstation endpoint.

Validated services:

- Wazuh Agent — running
- Sysmon64 — running
- CrowdSec — running
- CrowdSec Windows Firewall Bouncer — running

## Notes

Sysmon and CrowdSec provide additional endpoint telemetry / control coverage alongside the Wazuh agent. The repository documents their presence without publishing raw configuration files or credentials.
