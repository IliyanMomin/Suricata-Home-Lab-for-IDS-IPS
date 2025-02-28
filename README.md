# Suricata-Home-Lab-for-IDS-IPS

## Objective

This project aims to set up and configure a home lab for Suricata, an open-source Intrusion Detection System (IDS) and Intrusion Prevention System (IPS), to enhance network security monitoring and threat detection capabilities. By deploying Suricata on an Ubuntu server, the project will explore its signature-based detection, anomaly detection, and multi-threading capabilities to identify and analyze suspicious network activity. The ultimate goal is to gain hands-on experience with network security monitoring, incident response, and threat hunting while optimizing detection rules and minimizing false positives.

### Skills Learned

- Network Security & Threat Detection – Configured Suricata IDS/IPS to monitor and identify suspicious network activity.
- Linux System Administration – Installed, managed, and troubleshot Suricata on an Ubuntu server.
- Network Traffic Analysis & Threat Hunting – Used Nmap and log monitoring to analyze traffic and fine-tune detection rules.
- Cybersecurity Implementation & Incident Response – Customized Suricata rules and analyzed alerts to detect and mitigate threats.

## Steps

Let's now install Suricata onto our Ubuntu Server. 

### 1.Install our Ununtu Server
<p>
  Installing Ubuntu is pretty straightforward I'm not going to bore you with the installation process. Use the link provided and you can use VMware or VirtualBox.
</p>

<div>
  <a href="https://ubuntu.com/download/desktop" target="_blank">
    <img src="https://img.shields.io/badge/Download-Ubuntu%20Desktop-orange?logo=ubuntu&logoColor=white" alt="Download Ubuntu Desktop" />
  </a>
</div>

<p>Before we move towards the next steps we need to know what an IDS and an IPS is. An IDS is a tool that detects threats and attacks whilist an IPS is a tool that defends against the threat. Suricata can be deployed in both modes.</p>

<p>But why go for an IDS if IPS does the work for you?</p>

<p>Good question! We need to consider what if the alert could be a false postitive? Like the alert may seem it might be dangerous but it isn't. The IPS doesn't know if it's too good to be true so it can disrupt operations for no good reason.</p>

<p>Suricata is an advanced Intrusion Detection and Prevention System (IDS/IPS) that provides real-time network monitoring and threat detection. It supports signature-based and anomaly-based detection, allowing it to identify known attacks and suspicious activity. With multi-threading capabilities, Suricata efficiently processes high volumes of traffic while supporting multiple protocols like TCP, UDP, HTTP, DNS, and FTP. Additionally, it enables custom rule creation, giving users flexibility to define security policies and improve detection accuracy.</p>

<p>Suricata is used for network security monitoring, allowing real-time detection and analysis of suspicious traffic. It functions as both an Intrusion Detection System (IDS) and Intrusion Prevention System (IPS) to identify and block threats like malware, port scans, and brute-force attacks. Security teams rely on Suricata for threat hunting and incident response, using its detailed logs and alerts to investigate cyber threats. Additionally, it helps organizations comply with security regulations by monitoring network activity and ensuring data protection.</p>

<p>Let's now get started with the installation of Suricata.</p>

### 2.Installing Suricata on our Ubuntu Server
<p>
  Now we need to install Suricata onto our ubuntu server.
</p>

