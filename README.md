# Ralph Christian N. Altez

**Aspiring SOC Analyst** · BS Information Technology, Major in Information and Network Security · University of Makati

I build and document security monitoring labs where i deploy SIEMs, generate attack telemetry, write detection logic, and wire up alerting to practise the detection and response workflow end to end. Everything below is fully written up with architecture diagrams, configuration, and screenshots.

## Projects

### [Splunk SOC Home Lab — SIEM Detection & Alerting](https://github.com/P1nkhehe/Splunk-Home-Lab)

Splunk Enterprise as the SIEM, with Sysmon and Windows Security event logs forwarded from a monitored endpoint through the Universal Forwarder. Simulated an RDP brute-force attack with Hydra, wrote SPL detection logic on EventCode 4625, scheduled it as an alert mapped to **MITRE ATT&CK T1110**, and pushed notifications to Discord through a webhook script.

`Splunk` `SPL` `Sysmon` `Universal Forwarder` `Hydra` `Kali Linux` `MITRE ATT&CK`


<span style="color:red;">The updated Splunk home lab write-up now includes six incident reports, a native Wazuh marker response and a manual API marker request from the Splunk VM. Splunk alert-driven containment is the next stage, not a completed feature.</span>

From this I learned that these certificates are what verify the identity of the server while the user, password, and tokens are what identify the person or program that is making the request.

[My Splunk Homelab Documentation](https://github.com/P1nkhehe/Splunk-Home-Lab/blob/main/docs/updated-lab-documentation.md)

### [Enterprise Network Security Capstone](https://github.com/P1nkhehe/enterprise-network-security-capstone)

BSIT capstone (Project Technical Lead): an enterprise WAN-LAN infrastructure with multi-ISP failover, FortiGate high availability, HSRP, VLAN segmentation, and site-to-site IPsec VPN — monitored with **Wazuh** for file integrity, vulnerability detection, CIS benchmarking, and VirusTotal-integrated malware response. Validated with SSH brute-force, EICAR, and web application attack simulations, and evaluated against ISO/IEC standards.

`Wazuh` `FortiGate` `HSRP` `IPsec VPN` `VLAN` `VMware` `Burp Suite` `sqlmap` `ISO/IEC 27001`

## Skills

| Area | Tools & concepts |
|---|---|
| **SIEM & Detection** | Splunk (SPL, scheduled alerting), Wazuh (log collection, FIM, vulnerability detection, SCA, Active Response), Sysmon, Windows Event Log, MITRE ATT&CK |
| **Network Security** | FortiGate (policies, web filtering, application control, IPS, HA, VPN), TCP/IP, VLAN segmentation, HSRP, IPsec, multi-ISP failover, Cisco Packet Tracer |
| **Systems & Tooling** | Linux (Ubuntu), Windows 10, VMware, Kali Linux, Burp Suite, sqlmap, VirusTotal API |

## Currently

- Working through LetsDefend's phishing email analysis course — header forensics, SPF/DKIM/DMARC validation, IOC extraction and reputation checks — and building a hands-on analysis lab next.

## Contact

[LinkedIn](https://www.linkedin.com/in/ralph-altez/)
