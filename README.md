# CTI_Assignment_Dhruv_Patel

# CTI Assignment – Cyber Threat Mapping Using the Diamond Model

## Task 3: Diamond Model Vertex Extraction

The following analysis is based on the **CISA Advisory AA23-335A: IRGC-Affiliated Cyber Actors Exploit PLCs in Multiple Sectors, Including U.S. Water and Wastewater Systems Facilities**.

| **Vertex**     | **Extracted Information**                                                        | **Supporting Evidence from Report**                                                                                              |
|----------------|-----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| **Adversary**  | **IRGC-affiliated cyber actors** (Iranian state-sponsored actors)                | The advisory identifies **Iranian cyber actors** affiliated with the **Islamic Revolutionary Guard Corps (IRGC)** targeting U.S. critical infrastructure. |
| **Infrastructure** | **Exploited PLCs**, **compromised IT/OT systems**, **remote access tools**      | The advisory highlights the exploitation of **programmable logic controllers (PLCs)** and **remote access tools** to gain unauthorized access. |
| **Capability** | **Exploiting PLC vulnerabilities**, **data exfiltration**, **disruptive malware deployment** | The actors exploit vulnerabilities in **PLCs**, deploy **malware** to disrupt operations, and **exfiltrate** sensitive data from compromised systems. |
| **Victim**     | **U.S. critical infrastructure** (Water, Energy, and Wastewater systems)         | The advisory targets critical sectors such as **water**, **energy**, and **wastewater systems** in the U.S. as the victims of these cyber attacks. |

---

## Task 5: Threat Actor Profile Summary

The **adversary** identified in this report is an **Iranian state-sponsored cyber group**, specifically linked to the **Islamic Revolutionary Guard Corps (IRGC)**. According to **CISA Advisory AA23-335A**, these cyber actors have targeted U.S. **critical infrastructure sectors**, particularly **water** and **wastewater systems**, exploiting vulnerabilities in **programmable logic controllers (PLCs)** and **IT/OT systems** to gain unauthorized access.

These actors typically use **spear-phishing** or other remote access techniques to compromise vulnerable **PLCs**, which are essential to control systems in industries like **water management**. Once inside, they deploy **disruptive malware** to cause operational damage and **exfiltrate sensitive data**, which can include proprietary **intellectual property** and system configurations. The **Diamond Model** analysis reveals that the **adversary** uses **compromised IT/OT infrastructure** and **remote access tools** to execute **data theft** and **system disruption** strategies.

Mitigation strategies recommended by **CISA** include **patching** known vulnerabilities, enhancing **network segmentation** between IT and OT environments, and enforcing **multi-factor authentication (MFA)** for cloud access. Regular vulnerability scanning and **employee training** on phishing and ransomware threats are also crucial to prevent further breaches.

---

## Task 6: Reflection

### **1. How does the Diamond Model help in understanding threat actors?**
The **Diamond Model** helps to break down the entire attack process into four core components: **Adversary**, **Infrastructure**, **Capability**, and **Victim**. By understanding how these components interact, organizations can gain insights into how the adversary operates, what resources they rely on, and where the key vulnerabilities in their own systems may lie. This approach makes it easier to devise focused defense strategies.

### **2. What challenges did you face in identifying each vertex?**
The main challenge was identifying the **Infrastructure** component, as **PLCs** can be difficult to monitor and patch, especially in critical sectors like **water** and **energy**. Also, the **Adversary** attribution to **IRGC-affiliated actors** required reviewing patterns and techniques that linked them to previous attacks on similar targets.

### **3. How could this model support proactive defense strategies?**
The **Diamond Model** helps us anticipate the types of **infrastructure** and **capabilities** that adversaries will target. By identifying **VMware vulnerabilities** as a **common attack vector**, organizations can implement proactive measures such as **patching**, **multi-factor authentication (MFA)**, and **network segmentation**. Monitoring for specific **ransomware behaviors** and **credential-based attacks** can also enhance threat detection capabilities.

---

## Reference

https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-335a
