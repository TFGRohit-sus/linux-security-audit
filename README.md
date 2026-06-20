# linux-security-audit
Basic Linux security audit project covering users, file permissions, installed services, open ports, and security recommendations.
# Linux Security Audit

## Objective

Perform a basic security assessment of a Linux system.

## Tools Used

- Linux Terminal
- chmod
- ls
- ss
- cat

## Audit Tasks

### 1. User Enumeration

Used:

cat /etc/passwd

Purpose:

Identify all users configured on the system.

---

### 2. Permission Management

Created a test file and modified permissions.

Command:

chmod 600 confidential.txt

Result:

Restricted access to the file owner only.

---

### 3. Open Port Analysis

Command:

ss -tuln

Purpose:

Identify listening services and reduce unnecessary exposure.

---

## Security Recommendations

- Apply least privilege access.
- Restrict sensitive files.
- Monitor open ports.
- Limit administrative privileges.

## Skills Demonstrated

- Linux administration
- File permissions
- User management
- Basic security auditing
