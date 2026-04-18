# RECONNAISSANCE-AND-FOOTPRINTING

## Objective

- Differentiate passive vs active reconnaissance techniques.
- Perform OSINT to enumerate public-facing information about a target domain.
- Run basic active scanning using Nmap to discover hosts, open ports, and services.
- Produce a concise attack-surface Data Flow Diagram (DFD) and prioritize potential targets for further testing.

### Skills Learned

- Open-Source Intelligence (OSINT) & Passive Reconnaissance
- Active Scanning & Network Analysis
- Threat Modeling & Risk Assessment
- Attack Surface Prioritization
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Amass
- Recon-ng
- dnsenum
- dnsrecon
- whois
- cloud_enum
- theHarvester
- Shodan
- Apollo.io
- Nmap

### Process

- **Scope and Rule Definition:** Before technical work began, the boundaries of the engagement were established. This involved identifying the target domain and defining the Rules of Engagement, which restricted the consultant to using approved OSINT tools within a controlled Kali Linux lab environment.
- **Passive Reconnaissance (OSINT):** This phase focused on gathering information without making direct contact with the target's servers to avoid detection.
- **Active Reconnaissance (Scanning):** I shifted to direct interaction with the infrastructure to identify live services and defenses.
-  **Infrastructure Mapping and Analysis:** Data from the previous steps was synthesized to understand the backend architecture.
-  **Risk Assessment and Prioritization:** The final step involved analyzing the findings to identify the most critical security gaps.

### Outcome 

The project outcome is a comprehensive security baseline of the target domain's external attack surface, transitioning from raw data collection to a structured risk-prioritized roadmap for future security hardening. Ultimately, the report provided a "Low Risk Assessment" status as of April 16, 2026, based on the findings of the passive and active reconnaissance phases. It established that while the core infrastructure is modern and cloud-native, specific misconfigurations in staging environments and DNS protocols require immediate attention to prevent a breach.

## Detailed Report
<a href = "https://github.com/ch1n4x4/RECONNAISSANCE-AND-FOOTPRINTING/blob/main/_RECONNAISSANCE__FOOTPRINTING_REPORT_(1).pdf">Rconnaissance & Footprinting Report</a>

