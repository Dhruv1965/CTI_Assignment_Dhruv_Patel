# CTI_Assignment_Dhruv_Patel

## Task 3: Diamond Model Vertex Extraction

The following analysis is based on the CISA Alert **AA23-331A: Iranian Cyber Actors Exploit PLCs**, describing IRGC-affiliated cyber activity targeting U.S. critical infrastructure.

| **Vertex** | **Extracted Information** | **Supporting Evidence from Report** |
|-----------|----------------------------|--------------------------------------|
| **Adversary** | Iranian IRGC-affiliated cyber actors | Activity attributed to actors linked to Iran’s Islamic Revolutionary Guard Corps (IRGC). |
| **Infrastructure** | Exposed PLCs, attacker-controlled servers, VPN access points, misconfigured OT/ICS networks | CISA reports use of Internet-exposed PLCs and unsecured remote access infrastructure. |
| **Capability** | Password spraying, default credential abuse, PLC manipulation, ICS/OT exploitation tools | Advisory details weak credential exploitation and OT manipulation techniques. |
| **Victim** | U.S. water, energy, and manufacturing critical infrastructure sectors | CISA states victims include water facilities and other critical infrastructure operators. |

---

## Task 5: Threat Actor Profile Summary

The threat group being investigated in this assignment is an Iranian government-backed computer group that is linked to the Islamic Revolutionary Guard Corps (IRGC). As described in CISA Alert AA23-331A, these attackers have been hitting critical infrastructure in the US, with a major attention to water management, energy production and manufacturing. The primary goal of them seems to be to disrupt industrial processes through the attack on operation technology (OT) systems.

Extra access is more often gained using the weak or default passwords on publicly exposed programmable logic controllers (PLCs) and other industrial control system (ICS) programs. The other attack vectors are password spraying, misconfigured remote access services, and unauthorized VPN entry points. The actors once in the environment manipulate the set up of PLCs which may interfere with physical processes and physical services.

The analysis of the Diamond Model gives prominent relations between the adversary, the tools used, and the victims. The opponent is a state-sponsored team that is experienced in the exploitation of ICS/OT. Their structure comprises of compromised PLCs, servers that are controlled by the attackers and unsecured OT networks. They include capabilities of credit exploitation, OT manipulation, and targeting ICS with the help of cyber techniques. U.S. critical infrastructure organizations that are segmented poorly or whose authentication practices are weak are victims.

Strong passwords, multi-factor authentication, segmentation of the OT/IT network, and disabling all functions that are not in use, as well as constant monitoring of the suspicious activity are the recommendations of CISA. Such measures go a long way in minimizing threat and enhancing the security positioning of industrial control settings.

---

## Task 6: Reflection

### **1. How does the Diamond Model help in understanding threat actors?**
The Diamond Model has four basic segments that an intrusion is divided on Adversary, Infrastructure, Capability, and Victim. It assists the analysts to learn how the attackers behave, the motives and the technical processes in a systematic, relationship-oriented manner.

### **2. What challenges did you face in identifying each vertex?**
The most critical issue was to separate infrastructures and capabilities since there might be tools which lie in both domains. It was also challenging to make an attribution where the threat actor was mentioned indirectly in the report. The fact that information was dispersed in various parts meant that one had to read and correlate information carefully.

### **3. How could this model support proactive defense strategies?**
The model allows the defendants to recognize attack patterns, frequently exploited entry points, and targeted systems. This will enable organizations to build more control, improve surveillance of certain TTPs, and anticipate how attackers will act out in the future, moving toward a proactive defense, rather than reactive response.

