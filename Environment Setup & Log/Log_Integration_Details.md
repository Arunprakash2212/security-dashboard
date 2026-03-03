# Log Integration Details

## 1. Objective
To integrate multiple log sources into the SIEM for centralized monitoring and analysis.

---

## 2. Log Sources Integrated

- Firewall Logs
- Windows Event Logs
- VPN Logs

---

## 3. Integration Method

### Firewall Logs
- Configured firewall to forward logs via Syslog.
- Verified logs received in SIEM index.

### Windows Event Logs
- Installed log forwarding agent (e.g., Splunk Universal Forwarder).
- Configured to send Security and System logs.

### VPN Logs
- Configured VPN server to export logs.
- Imported logs into SIEM for monitoring.

---

## 4. Verification

- Confirmed logs are searchable in SIEM.
- Verified fields such as:
  - Source IP
  - Username
  - Event ID
  - Timestamp


## 5. Status
Log integration successfully completed and ready for rule creation.
