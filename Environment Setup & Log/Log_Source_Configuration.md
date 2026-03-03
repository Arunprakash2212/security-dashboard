# Log Source Configuration

## 1. Firewall Log Configuration

- Enabled logging on firewall device.
- Configured Syslog forwarding to SIEM server IP.
- Set log level to capture security events.
- Verified logs are being transmitted successfully.

---

## 2. Windows Event Log Configuration

- Installed log forwarding agent (e.g., Universal Forwarder).
- Configured inputs to collect:
  - Security logs
  - System logs
  - Application logs
- Set destination to SIEM server.
- Verified event logs are visible in SIEM.

---

## 3. VPN Log Configuration

- Enabled logging on VPN server.
- Configured export of authentication and connection logs.
- Forwarded logs to SIEM via Syslog or agent.
- Verified VPN login events are searchable.

---

## 4. Configuration Validation

- Confirmed real-time log ingestion.
- Checked important fields:
  - Source IP
  - Username
  - Event ID
  - Timestamp
- Ensured no parsing errors.
