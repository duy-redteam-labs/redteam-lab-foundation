# Lab Runbook

## Purpose
This runbook documents how to start, validate, and restore the Red Team Lab Foundation environment.

## Lab Components
- Kali Linux
- OWASP Juice Shop
- Ubuntu Syslog Server

## Startup Procedure
1. Open VirtualBox.
2. Start the Ubuntu Syslog Server VM.
3. Start the OWASP Juice Shop VM.
4. Start the Kali Linux VM.
5. Wait for all systems to finish booting before validation.

## Validation Procedure

### 1. Network Validation
From Kali Linux, verify that the lab systems are reachable and basic connectivity is working.

Evidence:
- `docs/screenshots/net-ok.png`

### 2. Juice Shop Validation
Verify that the OWASP Juice Shop service is up and accessible.

Evidence:
- `docs/screenshots/juiceshop-ok.png`

### 3. Logging Validation
Verify that the Ubuntu syslog server is running and logging is functioning as expected.

Evidence:
- `docs/screenshots/logging-ok.png`

## Recovery / Restore Procedure
1. Shut down the affected VM if needed.
2. Open VirtualBox Manager.
3. Select the target VM.
4. Restore the desired snapshot.
5. Start the VM again.
6. Re-run the validation steps after restore.

## Notes
- This lab is for local-only practice.
- No real-world targets are used.
- Snapshots are used for recovery, not as screenshot evidence.