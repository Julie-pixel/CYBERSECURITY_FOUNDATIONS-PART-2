 
**Topics Covered:** The Hacker Methodology, Pentesting Fundamentals

---

## 1) The Hacker Methodology

This room introduced the basic 5-step process that many attackers (and defenders) follow when testing systems.

### The 5 Steps (in my own words)

1. **Reconnaissance (Information Gathering)**  
   This is where we collect as much information as possible about the target before touching it.  
   Example: domains, IP ranges, technologies, open-source info.

2. **Scanning & Enumeration**  
   After collecting basic information, we probe the target to find open ports, services, versions, users, and possible weak points.  
   Example tools: Nmap, service enumeration tools.

3. **Gaining Access (Exploitation)**  
   In this stage, we try to use discovered vulnerabilities to get into the target system.  
   This could be weak passwords, outdated software, misconfigurations, etc.

4. **Maintaining Access (Post-Exploitation)**  
   Once access is achieved, attackers may try to keep access and move deeper into the environment.  
   Defenders study this stage to understand persistence and lateral movement risks.

5. **Covering Tracks / Reporting (Ethical Context)**  
   Malicious attackers may hide traces, but in ethical hacking our job is to **document everything clearly** and report findings responsibly so they can be fixed.

### What I Learned
- Hacking is usually a **structured process**, not random guessing.
- Each step builds on the previous one.
- As a beginner, understanding methodology is more important than rushing into tools.

---

## 2) Pentesting Fundamentals

This room gave me a beginner-level understanding of penetration testing and where it fits in cybersecurity.

### Key Points I Understood
- **Penetration testing** is a legal, authorized security test to find weaknesses before real attackers do.
- A pentester simulates real attack behavior in a controlled and ethical way.
- The purpose is to improve security posture, not to cause damage.
- Rules of engagement and scope are critical (what can and cannot be tested).

### Pentesting Process (High Level)
- Define scope and permission
- Gather information
- Identify vulnerabilities
- Attempt safe exploitation
- Document findings and recommendations
---
## Practical
ACME has approached you for an assignment. They want you to carry out the stages of a penetration test on their infrastructure. View the site (by clicking the green button on this task) and follow the guided instructions to complete this exercise.

1.Define scope and permission

<img width="987" height="525" alt="image" src="https://github.com/user-attachments/assets/f2fb9e03-5cc4-458f-979f-4c40d32d9a5f" />
<img width="996" height="519" alt="image" src="https://github.com/user-attachments/assets/cc1654e1-aef3-4b08-be4b-c6e394eb5fbf" />
2. Gather information
<img width="984" height="402" alt="image" src="https://github.com/user-attachments/assets/48128a1c-946e-40fb-92b7-e8404161020c" />
<img width="996" height="432" alt="image" src="https://github.com/user-attachments/assets/166aecfa-95b7-4a86-ab4f-e03629a5b101" />

3.Enumeration & Scanning
<img width="985" height="530" alt="image" src="https://github.com/user-attachments/assets/db5b099a-1173-4722-957c-ee654c2c08fc" />
<img width="921" height="464" alt="image" src="https://github.com/user-attachments/assets/0c4e4ae1-0ea7-486c-92b4-3f428d8857a7" />

4.Exploitation
<img width="994" height="602" alt="image" src="https://github.com/user-attachments/assets/e457caec-5f03-4fa7-b7a8-7a8f50641743" />

5.Post Exploitation
<img width="989" height="598" alt="image" src="https://github.com/user-attachments/assets/d37bcc0e-30fb-46c4-9787-0a58bd925473" />

6. Pentest Report
<img width="992" height="532" alt="image" src="https://github.com/user-attachments/assets/9fff813b-88f8-43ed-b7cd-ec58225b4157" />
<img width="985" height="488" alt="image" src="https://github.com/user-attachments/assets/f815b6ab-7e1d-4320-acc7-d6485e853423" />
---

### Why It Matters
- Helps organizations discover security gaps early.
- Reduces risk of real-world breaches.
- Gives practical evidence for security improvements.

---

## Challenges I Faced
- Remembering the difference between scanning, enumeration, and exploitation.
- Understanding that pentesting is as much about **reporting** as technical testing.

## How I Solved Them
- I rewrote each stage in simple words.
- I reviewed examples of each step and linked them to real attack scenarios.

---

## Final Reflection
These two rooms helped me build a strong foundation.  
I now understand that cybersecurity learning should follow a process: **think, map, test, and report**.  

---

