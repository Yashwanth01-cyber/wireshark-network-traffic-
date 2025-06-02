# wireshark-network-traffic-
Overview
This project involves analyzing a captured network traffic file using Wireshark to identify potential security vulnerabilities in web application communication. The analysis focused on HTTP traffic during a login process, revealing multiple issues related to data being transmitted in cleartext.

Contents
- `Wireshark_Traffic_Capture_Report_with_Images.docx`: Detailed penetration testing report with findings, recommendations, and supporting screenshots.
- Packet capture screenshots: Visual evidence of the captured HTTP traffic with credentials exposed.

Key Findings
- Credentials transmitted in plaintext over HTTP.
- No use of HTTPS or TLS encryption.
- Potential risk of session hijacking due to lack of secure cookie transmission.

Recommendations
- Migrate to HTTPS using TLS for all sensitive data transmission.
- Implement HSTS and secure cookie attributes.
- Educate users and developers on the risks of transmitting sensitive data without encryption.

Tools Used
- Wireshark
- Windows OS for packet capture environment

Author
Generated as part of a cybersecurity analysis task.
