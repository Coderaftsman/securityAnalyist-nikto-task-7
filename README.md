Nikto Vulnerability Scan Report

 Objective
Performed a vulnerability scan using Nikto on a web server.

Tool Used
Nikto

Target
http://127.0.0.1

Scan Command
nikto -h http://127.0.0.1 -output nikto_scan_results.txt

Findings
1. Missing Security Headers
- Risk: Clickjacking and data exposure

2. Directory Indexing Enabled
- Risk: Unauthorized file access

3. Outdated Server Version
- Risk: Known vulnerabilities can be exploited

Conclusion
The scan identified multiple vulnerabilities that should be fixed to improve security.

Recommendations
- Update server software
- Disable directory listing
- Add security headers
