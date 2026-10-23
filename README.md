# Network Traffic Forensics & Suspicious Activity Detection

A practical cybersecurity project focused on capturing and examining network traffic, understanding protocol behaviour, and documenting whether the traffic reviewed showed clear signs of suspicious activity.

**Project type:** Cybersecurity practical / minor project  
**Environment:** Kali Linux lab  
**Tools:** Wireshark, TCPdump, `nslookup`, `curl`

## Quick links

- **[Open the project report](https://ryots07.github.io/network-traffic-forensics/)**
- **[View all cybersecurity projects](https://ryots07.github.io/Portfolio/)**
- **[View this repository](https://github.com/ryots07/network-traffic-forensics)**

## Objective

Capture and analyse network traffic using packet-analysis tools, apply filters to focus on relevant conversations, examine common protocols, and document findings based on observable evidence rather than assuming that unusual traffic is malicious.

## What I worked on

- Captured live network traffic in a Kali Linux environment.
- Used Wireshark display filters to narrow traffic for closer inspection.
- Examined DNS requests and responses, TCP connections and handshake behaviour, SYN/SYN-ACK packets, retransmissions, and protocol statistics.
- Reviewed TLS traffic at the packet and connection level, without claiming to inspect encrypted application contents.
- Used TCPdump alongside Wireshark for command-line packet capture and inspection.
- Used supporting commands such as `nslookup` and `curl` to help investigate network behaviour.
- Recorded commands, filters, packet counts, observations and conclusions in the project report.

## Investigation workflow

1. **Capture** — collect traffic in the lab environment.
2. **Filter** — isolate relevant protocols, hosts and conversations.
3. **Inspect** — review packet fields, connection behaviour and protocol details.
4. **Correlate** — compare observations across Wireshark, TCPdump and supporting commands.
5. **Assess and report** — document what the available evidence does and does not show.

## Findings

No confirmed malicious or clearly abnormal activity was identified in the traffic reviewed during this practical. This conclusion applies only to the captured sample and the scope of the investigation; it does **not** establish that an entire network is free of threats.

## What this project demonstrates

- Basic packet capture and traffic inspection
- Familiarity with DNS, TCP and TLS traffic
- Use of Wireshark filters and TCPdump
- Evidence-based analysis and clear technical documentation
- Careful distinction between an observation and a confirmed security finding

## Scope

This was a controlled learning exercise using traffic available in the lab environment. The report documents the commands and observations from that investigation.

---

*Created by Samyak Gautam as part of practical cybersecurity learning.*
