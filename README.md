# Analyze-A-Network-Attack

Provided a sample scenario and Wireshark TCP/HTTP log, I investigated and analyzed a Denial of Service (DoS) attack targeting a web server. The website experienced connection timeouts due to an overwhelming number of incomplete TCP handshakes initiated by a malicious actor. This attack, known as a SYN flood, exploits the TCP three-way handshake protocol by sending numerous SYN requests without completing the connection, causing the server to hold open partial connections and exhaust site resources.

For this project, I used network security skills to read the provided TCP/HTTP log and identified errors and analyzed potential reasons to why the website was throwing timeouts.

<ins>Skills Used<ins>

- Network Security
- Wireshark TCP/HTTP log
- TCP Protocol
