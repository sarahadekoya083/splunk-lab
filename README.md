# splunk-lab
# Splunk Security Monitoring Labs

Network and Server Logs
A collection of cybersecurity lab exercises focused on security monitoring,
log analysis, and threat detection using Splunk SIEM. These labs simulate 
real-world scenarios including FTP activity tracking and attack detection.

## Labs Included

### Lab 1 – FTP Server Log Analysis (ftp-log.txt)
A simulated FTP server log file containing:
- Failed and successful login attempts
- File upload and download activity
- Timestamps, usernames, and IP addresses

Used as the primary data source ingested into Splunk for analysis.

### Lab 2 – Brute Force Attack Detection (Bruteforce_Attack.txt)
A Splunk SPL (Search Processing Language) query designed to:
- Identify repeated failed login attempts
- Extract usernames and IP addresses from logs
- Flag potential brute force attacks by counting failures per user/IP

### Lab 3 – Detection Queries (Dectection_Querries.txt)
A Splunk SPL query designed to:
- Detect successful logins across the environment
- Extract and group activity by user and IP address
- Support investigation of suspicious access patterns

## Tools Used
- Splunk SIEM
- SPL (Search Processing Language)
- FTP Server Logs

## Skills Demonstrated
- Log ingestion and parsing
- Threat detection query writing
- Brute force attack identification
- Security event monitoring

## Folder Structure
splunk-security-labs/
├── ftp-log.txt
├── Bruteforce_Attack.txt
├── Dectection_Querries.txt
└── README.md

## Author
Adekoya Sarah M. — [Cybersecurity]
