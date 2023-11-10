# NIST-CSF-Security-Incident-Report

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Objective](#objective)
4. [Incident Report Analysis](#incident_report_analysis)
5. [Notes](#notes)
6. [Reflections](#reflections) 


# Introduction <a name="introduction"> 
In order to learn about network-level vulnerabilities and network security, a simulated security incident report completed as part of the cybersecurity documentation portfolio and [Google's Coursera Cybersecurity Certificate](https://www.coursera.org/google-certificates/cybersecurity-certificate) 
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

The different steps of analyzing this cybersecurity incident and integrate your analysis into a general security strategy align with NIST's CSF's five core functions:

- **Identify** security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

- **Protect** internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

- **Detect** potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

- **Respond** to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

- **Recover** affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.

# Incident Report Analysis <a name="incident_report_analysis"> 

## Summary
A distributed denial of service (DDoS) assault against the company's internal network resulted in a security incident. The organization's network services abruptly stopped working during the attack. The internet network's devices were impacted, and access to network resources was impossible within the impacted network.

| Phase  | Description of what happened at each NIST CSF phase |
| --- | --- |
| Identify | After looking into the security incident, the cybersecurity team found that an improperly configured firewall had allowed a hostile actor to send a large number of ICMP Pings into the company's network. Through a denial-of-service attack, the attacker was able to overrun the company's network due to a weakness in the misconfigured firewall. |
| Protect | The network security team deployed an IDS/IPS system to filter out some ICMP traffic to the internal network based on suspicious characteristics and a new firewall rule to limit the rate of incoming ICMP packets in order to prevent further DDoS attempts. |
| Detect | The security team will install source IP address verification on the firewall to look for spoof IP addresses on incoming ICMP packets and network monitoring software to detect abnormal traffic patterns in order to detect new and similar unauthorized network intrusions and enhance the ability to detect these threats. |
| Respond | In order to limit the problem and start figuring out its main cause, the incident management team responded by blocking incoming ICMP packets, stopping all non-essential network activity, taking it offline, and restoring important network services.To enhance response protocols, security staff should receive training on this tool and modifications to incident response playbooks for the Detect and Protect phases should be included to any current documentation. Management must notify law enforcement of the DDoS attack as soon as possible, depending on the industry of the impacted firm and the severity of the disruption. (For instance, informing a nearby FBI Field Office of the DDoS problem) |
| Recover | The network experienced a two-hour downtime due to an attack, prompting the IT and Security teams to collaborate in restoring normal business operations. During the two-hour outage, the cybersecurity team kept the staff informed and organized a lessons learned session. They identified the root cause of the attack and proposed safeguards for future protection. Efforts to improve response and recovery times, aiming for faster restoration than the initial two hours, will be explored after implementing safeguards in the protect and detect phases. Considering a Cyber Insurance provider for recovery assistance and consultation advice is also on the table to mitigate revenue loss. Following this, a thorough investigation will be launched to pursue legal actions against those responsible for the cyberattack. The focus will be on determining the extent of the damage caused by the attack and taking appropriate steps based on the findings. |


# Notes <a name="notes"> 

As a cybersecurity student, this task posed a challenge that I handled quite effectively in the beginning. However, I encountered difficulty in the process by incorporating excessive details, exceeding the exemplar example's scope. Ensuring that my written documentation flowed smoothly while explaining and breaking down each step proved to be a bit tricky. Despite this, I came remarkably close to matching the exemplar.
An important consideration emerged—planning a penetration testing exercise to assess the organization's security posture and the effectiveness of the implemented safeguards. It's a proactive approach, emphasizing the importance of testing security to prevent regrets in the event of a breach.

[The whitepaper titled "Comprehending and Addressing Distributed Denial-of-Service Attacks" released by CISA.](https://www.cisa.gov/sites/default/files/publications/understanding-and-responding-to-ddos-attacks_508c.pdf)


Article by NIST outlining recommendations for effectively recovering from a cyberattack.
[How to Recover from a Cyber Attack | NIST](https://www.nist.gov/blogs/manufacturing-innovation-blog/how-recover-cyber-attack#:~:text=Consider%20Cyber%20Insurance%20for%20Increased%20Recovery%20Capability%20Like,assist%20in%20identifying%20the%20extent%20of%20damage%20caused)

# Reflections <a name="reflections"> 
As a cybersecurity student, tackling this task was initially challenging, but I performed well. The difficulty arose when I found myself including excessive details, going beyond the exemplar example for the assignment. Ensuring my written documentation flowed smoothly to effectively explain and break down each process became a struggle. Despite this, I came remarkably close to aligning with the exemplar example.
