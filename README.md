# CODTECH-task1
Name: Priyanshu Vijay Singh
Company: CODTECH IT SOLUTIONS
ID•. CT08FFC
Domain: Cyber Security
Duration: 20 dec 2024 to 20 jan 2025
Mentor: Neela Santhosh Kumar


Project 1: Vulnerability Scanning Tool
Description:
This project is a Python-based vulnerability scanning tool designed to identify common security issues in networks and websites. It can scan a network for open ports, outdated software versions, and misconfigurations in HTTP headers. The tool is a starting point for understanding security vulnerabilities and can be further enhanced for more advanced scanning.

Features:

Open Port Scanning: Identifies open ports on a given host using the socket library.
Outdated Software Detection: Checks HTTP response headers to identify the server software and its version, flagging potential outdated versions.
Misconfiguration Scanning: Looks for missing security headers like X-Frame-Options, Strict-Transport-Security, and X-Content-Type-Options.
How It Works:

The user specifies a target (IP or domain) and chooses to scan a network or a website.
For network scans, the script checks the first 1024 ports for open connections.
For website scans, it analyzes HTTP headers for outdated software and missing configurations.
Applications:

Network security assessments.
Basic web application hardening by identifying misconfigurations.
