<h1>🛡️ Defensive Security Intro — TryHackMe</h1>

<h2>Lab Summary & Notes</h2>

<p>
This room introduced the fundamentals of defensive security, focusing on how cybersecurity teams 
prevent, detect, and respond to intrusions. Unlike offensive security, which seeks vulnerabilities 
to exploit, defensive security emphasizes protecting systems, monitoring activity, analyzing threats, 
and reacting effectively when incidents occur. This lab helped me understand how SOC teams, DFIR 
analysts, and threat intelligence researchers work together to defend an organization.
</p>

<h2>🚀 Overview</h2>

<p>In this lab, I learned how to:</p>
<ul>
    <li>Understand the primary goals of defensive security: prevention and detection/response</li>
    <li>Recognize the responsibilities of a Security Operations Center (SOC)</li>
    <li>Explain how Threat Intelligence identifies adversaries and predicts attacks</li>
    <li>Understand Digital Forensics & Incident Response (DFIR)</li>
    <li>Differentiate between static and dynamic malware analysis</li>
    <li>Investigate alerts in a simplified SIEM environment</li>
</ul>

<p>
This was my first hands-on exposure to the defensive side of cybersecurity. It demonstrated how 
important continuous monitoring, analysis, and rapid response are in protecting an organization 
from cyber threats.
</p>

<h2>🔧 Tools & Concepts Used</h2>

<strong>Security Information and Event Management (SIEM)</strong>
<p>
A SIEM aggregates logs from multiple sources and correlates events to help analysts detect suspicious activity. 
In the simulation, I used a simplified SIEM interface to review alerts and follow an investigation trail.
</p>

<strong>Firewalls & Intrusion Prevention Systems (IPS)</strong>
<p>
Core preventative tools that block unauthorized access and known threats based on rules or signatures.
</p>

<strong>Logging & Monitoring Systems</strong>
<p>
Essential components that track activity across devices, detect anomalies, and alert analysts of potential compromise.
</p>

<h2>🧠 What I Did</h2>

<h3>1. Explored the foundations of defensive security</h3>
<p>
I learned how defensive security focuses on preventing incidents through patching, asset management, 
user awareness, monitoring, and incident preparation.
</p>

<h3>2. Studied how a SOC operates</h3>
<p>
I reviewed how SOC analysts monitor for vulnerabilities, policy violations, unauthorized logins, 
and network intrusions, determining whether alerts represent false positives or real threats.
</p>

<h3>3. Learned about Threat Intelligence</h3>
<p>
I explored how organizations gather information about potential adversaries—their tactics, motives, 
and tools—to build a threat-informed defense.
</p>

<h3>4. Reviewed the core components of DFIR</h3>
<p>
I learned how digital forensics examines file systems, logs, and memory images, while incident response 
focuses on containment, eradication, recovery, and documenting lessons learned.
</p>

<h3>5. Studied malware analysis concepts</h3>
<p>
I compared static malware analysis (examining malware without executing it) and dynamic analysis 
(running malware in a controlled environment to observe behavior).
</p>

<h3>6. Completed the SIEM investigation</h3>
<p>
I used the interactive SIEM simulation to examine suspicious login attempts, unusual IP addresses, 
and correlated events. This led me to the final alert containing the flag (not included here).
</p>

<h2>📘 Key Takeaways</h2>

<ul>
    <li>Defensive security requires continuous monitoring and analysis—not just prevention.</li>
    <li>A SOC acts as the central hub for detecting and responding to suspicious activity.</li>
    <li>Threat Intelligence helps predict adversaries’ behavior and plan defense strategies.</li>
    <li>DFIR is essential for understanding how incidents happened and restoring systems safely.</li>
    <li>Malware analysis provides insight into attacker tools and behavior.</li>
    <li>Investigating SIEM alerts builds essential skills for SOC and blue-team roles.</li>
</ul>

<p>
This room helped build my foundational understanding of how defenders safeguard networks and respond 
to cyber threats.
</p>

<h2>📂 Repository Structure</h2>

<p>/TryHackMe/</p>
<p>/Defensive-Security-Intro/</p>
<p>README.md</p>

<h2>📝 Next Steps</h2>

<ul>
    <li>Practice SIEM investigations using ELK, Splunk, or Wazuh</li>
    <li>Explore further blue-team rooms such as “SOC Level 1” and “Blue Primer”</li>
    <li>Learn more about Windows Event Logs and Linux auditing</li>
    <li>Experiment with home lab monitoring using Sysmon, Zeek, or Suricata</li>
    <li>Continue progressing toward SOC Analyst or DFIR career paths</li>
</ul>
