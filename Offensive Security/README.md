# Offensive Security Projects 

**1. Network Security : Nmap**

  * **Responsibility** : Perform a server network scan test and see what ports are open, what services are running, etc.

  * **Tools** : Nmap
    
  * **Findings** : The FTP service port is open. FTP login attempts fail, but this is a vulnerability worth noting. This vulnerability can be exploited by attackers if not immediately noticed.

  <a href="https://github.com/AnggaSOC/Cyber/tree/main/Defensive%20Security/Email%20Phishing%20Analysis"><kbd>View Detail</kbd></a>

**2. Splunk: Incident Investigation**

  * **Responsibility** : Investigating the timeline of a website hacking incident: affected assets, attackers, techniques, points of entry, etc.
  
  * **Tools** : Splunk Enterprise
  
  * **Findings** : Wayne Enterprise was hit by a cyberattack; the “iamreallynotbatman” website was compromised. The incident timeline was successfully mapped using the cyber kill chain method, and all relevant evidence was identified.

  <a href="https://github.com/AnggaSOC/Cyber/tree/main/Defensive%20Security/Email%20Phishing%20Analysis"><kbd>View Detail</kbd></a>

**3.  Wazuh : Endpoint Monitoring and Threat Detection**

  * **Responsibility** : Design and implement SIEM design to monitor and detect threats on endpoints, integrate SIEM with IDS
  
  * **Tools** : Wazuh, Suricata IDS, Linux Server
  
  * **Findings** : IDS successfully sends alerts when network scanning occurs from external parties, and Wazuh successfully records activity in important directories on the Linux server.

  <a href="https://github.com/AnggaSOC/Cyber/tree/main/Defensive%20Security/Wazuh%20Monitoring%20and%20Threats%20Detection"><kbd>View Detail</kbd></a>

**4.  Malware Detection with Splunk Enterprise and Sysmon**

  * **Responsibility** : Install Sysmon on endpoint and integrate to Splunk Enterprise, monitor employee activity on endpoint
  
  * **Tools** : Splunk Enterprise, Windows 10, Windows 11
  
  * **Findings** : An employee's PC was infected with malware originating from the file 'Finance_Report2026' downloaded via Google Drive. The malware file contained a script to exfiltrate data on the infected PC. Company data was successfully stolen.

  <a href="https://github.com/AnggaSOC/Cyber/tree/main/Defensive%20Security/Splunk%20and%20Sysmon%20Threats%20Detection"><kbd>View Detail</kbd></a>

**5.  Automation Respon System**

  * **Responsibility** : Design, implement, and integrate wazuh SIEM with shuffle automation to automate incident response.
  
  * **Tools** : Wazuh, Linux server, Windows 11, Kali Linux, Shuffle, Email, Jira
  
  * **Findings** : All incident responses are successfully automated with shuffle: blocking DoS-DDoS attacks, automatic response to malware, automatic incident ticket creation, and real-time email notifications to the incident response team.

  <a href="https://github.com/AnggaSOC/Cyber/tree/main/Defensive%20Security/Splunk%20and%20Sysmon%20Threats%20Detection"><kbd>View Detail</kbd></a>

