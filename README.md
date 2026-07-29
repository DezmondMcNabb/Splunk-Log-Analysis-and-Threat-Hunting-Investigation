# Splunk Security Log Analysis & Threat Hunting Project

## Overview

This project showcases a comprehensive security log analysis and threat hunting investigation conducted with **Splunk Enterprise**. Using a dataset, the analysis focused on uncovering suspicious authentication behavior, reviewing both successful and failed SSH login attempts, examining malicious source IP addresses, and identifying HTTP 500 Internal Server Error events within web server logs.

---

## Objectives

The primary goals of this investigation included:

- Import and verify log data within Splunk.
- Examine available log sources and associated sourcetypes.
- Analyze failed SSH authentication events.
- Review successful SSH logins for the user `djohnson`.
- Investigate repeated authentication failures originating from a suspicious IP address.
- Identify source IPs generating excessive failed login attempts.
- Detect and evaluate HTTP 500 Internal Server Error events.

---

## Key Activities

- Imported and validated data in the `example` index.
- Explored log sources and identified relevant sourcetypes.
- Performed SSH authentication investigations using SPL (Search Processing Language).
- Analyzed brute-force and password-guessing attack patterns.
- Extracted and evaluated source IP addresses based on authentication frequency.
- Investigated web server logs for HTTP 500 errors.
- Conducted additional threat hunting to identify the most frequently targeted user accounts.
- Documented findings and provided security recommendations based on the investigation.

---

## Findings

The investigation revealed:

- **100,000+** indexed events analyzed.
- Multiple failed SSH authentication attempts consistent with brute-force activity.
- Successful SSH sessions associated with user `djohnson`.
- Several external IP addresses responsible for a high volume of failed login attempts.
- Repeated attacks targeting privileged accounts such as `root`, `administrator`, and `admin`.
- **781** HTTP 500 Internal Server Error events identified within the web server logs.

---

## Skills Demonstrated

- Splunk Enterprise
- SPL (Search Processing Language)
- Log Analysis
- Threat Hunting
- SSH Authentication Analysis
- Security Event Monitoring
- Incident Investigation
- Incident Triage
- Threat Detection
- Security Log Analysis
- Cybersecurity Reporting
- Brute-Force Detection
- Web Server Log Analysis

---

## Tools & Technologies

- **Splunk Enterprise**
- **Search Processing Language (SPL)**
- **Linux Authentication Logs**
- **SSH Log Analysis**
- **Apache Web Logs**
- **Threat Hunting Methodology**

---

## Project Outcome

This project demonstrates hands-on experience using Splunk Enterprise to ingest, search, and analyze security logs for indicators of compromise. Through the use of SPL queries, authentication analysis, IP investigation, and web server log review, the project highlights practical skills in threat hunting, incident investigation, and cybersecurity reporting.
