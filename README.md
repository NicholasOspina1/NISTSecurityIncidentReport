# NIST CSF Security Incident Report


# Description <a name="description"> 
I created a NIST CSF Security Incident Report for a fictional company. This assessment was completed as a component of my cybersecurity portfolio and as part of the <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Google Cybersecurity Professional Certificate</a> on Coursera, specifically in the  <a href='https://www.coursera.org/learn/networks-and-network-security'> "Connect and Protect: Networks and Network Security" </a> Course.


The goal of this project is to create a quality cybersecurity incident report while applying the CSF in order to build trust and improve security practices within the organization. The CSF is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. The CSF is scalable and can be applied in a wide variety of contexts. Knowing how to identify which security measures to apply in response to business needs will help determine which are the best available options when it comes to network security.

# Scenario <a name="scenario"> 
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets

- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

- Network monitoring software to detect abnormal traffic patterns

- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics


# Objective  <a name="objective"> 
You are tasked with using this security event to create a plan to improve your company’s network security, following _the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF_). 

The different phases required for investigating this cybersecurity incident and incorporating your discoveries into a comprehensive security strategy are aligned with the five core functions of NIST's CSF:

- **Identify** security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

- **Protect** internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

- **Detect** potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

- **Respond** to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

- **Recover** affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.

# My Incident Report Analysis <a name="incident_report_analysis"> 

## Summary

The moment all network services abruptly stopped responding, the business experienced a security incident. The distributed denial of service (DDoS) attack that the cybersecurity team discovered was responsible for the outage that occurred through a surge of ICMP packets. In order to recover critical network services, the team reacted by stopping the attack and all non-critical network services.

| Phase  | Description |
| --- | --- |
| Identify | An ICMP flood attack was used to attack the company by a malicious actor or actors. The internal network was impacted. It is essential to secure and restore every critical network resources. |
| Protect | In order to reduce the volume of incoming ICMP packets, the cybersecurity team implemented a new firewall rule. Additionally, an IDS/IPS system was set up to filter out some ICMP traffic based on suspicious behaviors. |
| Detect | The firewall's source IP address verification feature was set up by the cybersecurity team to check for spoofed IP addresses from incoming ICMP packets. Network monitoring software was also put into place to look for unusual patterns of traffic. |
| Respond | The cybersecurity team will isolate impacted systems in the event of future security incidents to stop further network downtime. Any vital systems and services that were interfered with by the incident will be attempted to be restored. The team will then examine network logs to look for unusual or suspicious activity. Additionally, the team will notify upper management and, if necessary, the relevant legal authorities of every incident. |
| Recover | Access to network services must be returned to a fully operational state to recover from a DDoS attack by ICMP flooding. The firewall may be used in order to prevent future external ICMP flood attacks. Afterwards, to decrease internal network traffic, all non-critical network services should be terminated. Next, it is best to start restoring essential network services. Lastly, all non-critical network systems and services can be restarted after the flood of ICMP packets has timed out. |


