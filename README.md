# Cisco Router Centralized Syslog Configuration

Centralized Syslog Logging Setup using Ubuntu Server and Rsyslog for Cisco Router R1.

## Environment Details
- **Syslog Server IP:** 192.168.200.130 (Ubuntu Server)
- **Cisco Router IP:** 192.168.200.132 (R1)
- **Protocol & Port:** UDP 514

## Configurations
- **Rsyslog Filter Rule:** `/etc/rsyslog.d/10-cisco.conf`
- **Destination Log File:** `/var/log/cisco/router.log`

## Cisco Router Settings
```text
logging trap debugging
logging host 192.168.200.130
