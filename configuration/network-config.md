# Network Configuration Notes

The Wazuh server uses separate paths for the lab network and dashboard access.

- `192.168.1.103` — Wazuh manager address used by the Windows agents in this lab.
- `192.168.56.103` — host-only dashboard access address.
- `enp0s9` — host-only interface on `SOC-WAZUH`.
- A dedicated Netplan file `/etc/netplan/99-hostonly.yaml` was created with `192.168.56.103/24` on `enp0s9`.
- The file permissions were tightened to `600` before applying Netplan.
- From the Windows host, `Test-NetConnection 192.168.56.103 -Port 443` returned `TcpTestSucceeded : True`.

Never publish secrets, private keys, or full credential-bearing configuration files.
