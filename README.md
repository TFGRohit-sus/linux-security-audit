# Linux Security Audit

## Objective

Perform a basic security assessment of a Linux system to understand users, permissions, administrator access, and network exposure.

## Tasks Performed

### 1. User Enumeration

Command:

cat /etc/passwd

Purpose:

Identified user accounts configured on the system.

### 2. Administrator Privilege Verification

Command:

getent group sudo

Purpose:

Verified users with elevated (administrator) privileges.

### 3. File Permission Management

Commands:

touch confidential.txt

chmod 600 confidential.txt

Purpose:

Restricted access to a sensitive file using the principle of least privilege.

### 4. Open Port Analysis

Command:

ss -tuln

Purpose:

Inspected listening services to understand the system's attack surface.

## Security Recommendations

- Follow the principle of least privilege.
- Restrict access to sensitive files.
- Regularly review administrator accounts.
- Monitor unnecessary open ports.

## Skills Demonstrated

- Linux fundamentals
- User enumeration
- Privilege management
- File permissions
- Basic security auditing

## Evidence

Screenshots demonstrating:

- User enumeration
- Administrator privilege verification
- File permission modification
- Open port analysis

Repository URL:

https://github.com/TFGRohit-sus/linux-security-audit
