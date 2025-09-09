# dhcp-pcap-analysis
---
it's DHCP-focused, a beginner-friendly pcap analysis. in which try to find out basic info through wireshark.

This repository contains a basic triage-level analysis of a DNS packet capture (dns.cap) file using Wireshark. It demonstrates how to inspect DNS queries and responses, apply filters, identify anomalies, and document findings — a foundational skill in SOC and Digital Forensics workflows.

📁<h2> FILES INCLUDED </h2>
 <hr>
- dhcp.cap - original DHCP packet capture file.
- analysis/dhcp_analysis_notes.md — Step-by-step analysis with findings
- filters.txt — Wireshark filters used during analysis.
    ---

🔧 <h2>Tools Used</h2>
<hr>
- Wireshark – for packet inspection
- Basic Linux commands (optional)
- Git & GitHub – version control and repo hosting
  ---
🧪 <h2> Analysis Performed </h2>
<hr>
Extracted and examined all DHCP packets
Differentiated DHCP queries and responses
Observed domain name queries and resolved IPs
Checked for repeated queries and anomalous responses
Identified potential triage flags (e.g., multiple responses to a single query)
 ---

 <h2>🧠 Key Learnings</h2>
 <hr>
How DHCP queries and responses work
How to use Wireshark filters for DHCP analysis
How to identify basic indicators of compromise (IOCs) in DHCP traffic
Importance of triage in SOC workflows
---
<h2>📌 Use Case</h2>
<hr>
This repo can help:
Students learning cybersecurity fundamentals
Beginners practicing packet analysis
SOC Level 1 aspirants trying triage basics
Anyone exploring DHCP packet behavior
---
<h2>📬 Contact</h2>
<hr>
If you're also learning cyber forensics or SOC tools and want to collaborate or ask questions:
📧 Email: nitinnsharma48@gmail.com
🐦 Twitter: https://x.com/cyberNSharma
🔗 LinkedIn: www.linkedin.com/in/cybernsharma
---
<h2>⭐ Give a Star!</h2>
<hr>
If you found this project helpful, consider giving it a ⭐ to support more beginner-friendly cybersecurity repo
---



 

 

