INCIDENT RESPONSE REPORT FOR DENIAL-OF-SERVICE (DOS) ATTACK

🔍 OVERVIEW:

This project demonstrates the analysis and response to a simulated cybersecurity incident involving a Denial-of-Service (DoS) attack using the Slowloris tool. The attack was targeted at a web server hosted in a VMware environment on port 80 (HTTP). Wireshark was utilized to capture and analyze network traffic, and mitigation steps were implemented.

✨ FEATURES:

Wireshark Analysis: Comprehensive packet capture and analysis of attack traffic.

Root Cause Analysis: Identification of server vulnerabilities to Slowloris attacks.

Mitigation Steps: Actions taken to stop the attack and restore server functionality.

Recommendations: Technical and administrative strategies to prevent similar attacks.

⚙️ PREREQUISITES:

TOOLS USED:

VMware (Virtual Machine hosting the web server)

Metasploitable 2 (Web server environment)

Wireshark (Network traffic analyzer)

Slowloris (DoS attack simulation tool)

SYSTEM REQUIREMENTS:

Any system capable of hosting a virtual machine and running Wireshark.

📂 FILES INCLUDED:

Incident_Response_Report.docx: Detailed report documenting the simulated incident.

Wireshark_Capture_Logs.pcap: Packet capture logs from Wireshark.

Slowloris_Output.txt: Output logs from the Slowloris attack tool.

Server_Logs.txt: Web server logs showing evidence of the attack.

📜 PROJECT DETAILS:

🛠️ STEPS PERFORMED:

Set up a vulnerable web server using Metasploitable 2 in a VMware environment.

Used Slowloris to simulate a DoS attack targeting port 80.

Captured and analyzed network traffic using Wireshark.

Documented the root cause, mitigation, and preventive measures.

🔑 KEY FINDINGS:

The Slowloris attack overwhelmed the server’s connection pool by sending numerous incomplete HTTP requests.

The server lacked adequate timeout settings for incomplete connections.

🚀 USAGE:

Download all files from the repository.

Open Wireshark_Capture_Logs.pcap in Wireshark to analyze the captured traffic.

Refer to Incident_Response_Report.docx for detailed analysis and recommendations.

Implement the suggested mitigation strategies and recommendations to secure similar environments.

📈 RECOMMENDATIONS FOR FUTURE WORK:

Enhance server configurations to handle incomplete connections.

Conduct further penetration tests to identify additional vulnerabilities.

Regularly update software and maintain server security patches.
