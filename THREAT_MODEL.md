# IoT Device Threat Model

## 1. Device Description

**Device Name:** SmartHome Sensor
**Function:** Monitors temperature, humidity, and motion; sends data to cloud; allows remote control via mobile app.

## 2. Assets
- Sensor data (temperature, humidity, motion)
- Device firmware
- Cloud credentials/API keys
- User personal information
- Network connectivity

## 3. Potential Threats
- Unauthorized access to device or data
- Data interception during transmission
- Firmware tampering or malicious updates
- Denial of service (DoS) attacks
- Physical theft or tampering
- Privacy violations (tracking user behavior)

## 4. Vulnerabilities
- Weak/default passwords
- Unencrypted communication (Wi-Fi, cloud)
- Outdated firmware
- Insecure API endpoints
- Lack of physical security

## 5. Mitigations
- Enforce strong password policies
- Use encrypted communication (TLS/SSL)
- Regular firmware updates and integrity checks
- Secure API authentication and authorization
- Physical device tamper detection

## 6. Summary
This basic threat model identifies key assets, threats, vulnerabilities, and mitigations for a generic IoT device. It should be reviewed and updated as the device design evolves.
