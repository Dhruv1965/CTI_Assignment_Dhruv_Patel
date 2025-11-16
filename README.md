# CTI_Assignment_Dhruv_Patel

## ## Task 3: Diamond Model Vertex Extraction

The following analysis is based on the CISA Alert **AA23-331A: Iranian Cyber Actors Exploit PLCs**, describing IRGC-affiliated cyber activity targeting U.S. critical infrastructure.

| **Vertex** | **Extracted Information** | **Supporting Evidence from Report** |
|-----------|----------------------------|--------------------------------------|
| **Adversary** | Iranian IRGC-affiliated cyber actors | Activity attributed to actors linked to Iran’s Islamic Revolutionary Guard Corps (IRGC). |
| **Infrastructure** | Exposed PLCs, attacker-controlled servers, VPN access points, misconfigured OT/ICS networks | CISA reports use of Internet-exposed PLCs and unsecured remote access infrastructure. |
| **Capability** | Password spraying, default credential abuse, PLC manipulation, ICS/OT exploitation tools | Advisory details weak credential exploitation and OT manipulation techniques. |
| **Victim** | U.S. water, energy, and manufacturing critical infrastructure sectors | CISA states victims include water facilities and other critical infrastructure operators. |

---

## Task 5: Threat Actor Profile Summary

The threat actor analyzed in this assignment is an Iranian government-linked cyber group associated with the Islamic Revolutionary Guard Corps (IRGC). According to CISA Alert AA23-331A, these actors have targeted critical infrastructure in the United States, focusing on water management, energy production, and manufacturing sectors. Their main intent appears to be the disruption of industrial processes by compromising operational technology (OT) systems.

Initial access is usually obtained through weak or default passwords on publicly exposed programmable logic controllers (PLCs) and other industrial control system (ICS) devices. Other attack vectors include password spraying, misconfigured remote access services, and unauthorized VPN entry points. Once inside the environment, the actors manipulate PLC configurations, potentially disrupting physical processes and services.

Diamond Model analysis highlights clear relationships among the adversary, their tools, and their victims. The adversary is a state-affiliated group skilled in ICS/OT exploitation. Their infrastructure includes compromised PLCs, attacker-controlled servers, and unsecured OT networks. Their capabilities involve credential exploitation, OT manipulation, and ICS-targeted cyber techniques. Victims are U.S. critical infrastructure organizations with insufficient segmentation or weak authentication practices.

Mitigation strategies recommended by CISA include strong password enforcement, multi-factor authentication, OT/IT network segmentation, disabling unused PLC functions, and continuous monitoring for unusual activity. These measures significantly reduce risk and strengthen the security posture of industrial control environments.

---

## Task 6: Reflection

### **1. How does the Diamond Model help in understanding threat actors?**
The Diamond Model breaks an intrusion into four main components—Adversary, Infrastructure, Capability, and Victim. This helps analysts understand attacker behavior, motivations, and technical operations in a structured, relationship-based format.

### **2. What challenges did you face in identifying each vertex?**
The primary challenge was distinguishing between “infrastructure” and “capability,” as some tools could fall into both categories. Attribution was also difficult when the report referenced the threat actor indirectly. Information being scattered across different sections required careful reading and correlation.

### **3. How could this model support proactive defense strategies?**
The model enables defenders to identify attack patterns, commonly abused entry points, and targeted systems. This allows organizations to strengthen controls, enhance monitoring for specific TTPs, and predict future attacker behavior—shifting from reactive response to proactive defense.

