<div align="center">
  
# Capstone: Fort Faux 

[Back to Portfolio](https://github.com/fenndw)

</div>

---

## Overview
Fort Faux is a mid‑complexity network infrastructure project built as the capstone for the Information Technology Systems Management and Security (ITSMS) program at NSCC. As the project lead, I coordinated a four‑person team to design, deploy, secure, and test a (semi)‑replicated educational center network. The goal was to apply the full breadth of our program knowledge—networking, virtualization, security, monitoring, documentation, and incident response—into one cohesive, fully operational environment.

Once the environment was built, we executed Red Team vs. Blue Team exercises to evaluate the network’s resilience, validate our monitoring stack, and practice real‑world defensive operations.

---

## Objectives
Our project goals were defined early and guided the entire build:

1. Design and document a mid‑complexity network infrastructure modeled after an educational center  
2. Configure and install all required hardware and software  
3. Deploy Security Onion and Wazuh for security monitoring and alerting  
4. Ensure the environment is fully functional and stable  
5. Research, plan, and execute Red Team vs. Blue Team exercises  
6. Produce complete documentation from planning → deployment → testing  
7. Demonstrate teamwork and applied knowledge across all ITSMS disciplines  

---

## Relevance to the ITSMS Program
Fort Faux directly ties into the core learning outcomes of the program:

- **Network Infrastructure:** UniFi router + Switch Lite 8 PoE, subnetting, routing  
- **NOS Administration:** Windows Server 2025 with DNS, DHCP, domain services  
- **Enterprise Management & Automation:** Imaging and deployment using Rufus + custom ISO  
- **Data Fundamentals:** SQL Server database integration  
- **Information Security Practices:** Security Onion + Wazuh monitoring stack  
- **Hardware & Security:** Physical server, virtual servers, Windows clients, monitoring console  
- **Project Quality Assurance:** Full project charter, documentation, and milestone tracking  

---

## Project Scope

### **In Scope**
- Replicating an educational center’s network infrastructure  
- Installing and configuring all required hardware and software  
- Deploying Security Onion and Wazuh  
- Conducting Red Team vs. Blue Team exercises  

### **Out of Scope**
- Website development or heavy coding  
- Linux Netplan configuration  
- VLAN implementation  
- Backup theory (beyond practical snapshots and recovery steps)  

---

## Deliverables
1. Network topology diagram + configuration files + full documentation  
2. Zero‑trust‑aligned security measures  
3. Security Onion and Wazuh monitoring stack  
4. Fully functional environment with screenshots of key configurations  
5. Blue Team incident response playbook + disaster recovery plan  
6. Red Team exercise playbook  
7. Final written report covering design decisions, troubleshooting, known issues, and references  

---

## Timeline & Milestones

| Milestone | Target Week | Status | Owner | Description |
|----------|-------------|--------|--------|-------------|
| 1 | Week 1–2 | ✔️ | Fenn | Requirements, threat model, architecture diagram |
| 2 | Week 3–4 | ✔️ | Amanda | Environment setup, baseline tests |
| 3 | Week 5–6 | ✔️ | Ash | Core feature build, internal review |
| 4 | Week 7–8 | — | Patrick | Security hardening, integration, performance tests |
| 5 | Week 9–10 | — | Patrick | Failure drills, documentation draft |
| 6 | Week 11–13 | — | Fenn | Final demo, report, lessons learned |

---

## Hardware & Resources
All work was completed in the NSCC Hardware Lab (Room 312).

### **Hardware Used**
- Windows Server 2025 (physical)  
- Two Windows 11 Education clients (physical)  
- Three monitors, keyboards, mice  
- UniFi Router + Switch Lite 8 PoE  
- USB‑A flash drive for imaging  
- Five Ethernet cables  
- Personal laptops for research  

### **Software / Platforms**
- Windows Server 2025  
- Windows 11 Education  
- Hyper‑V virtual machines  
- Security Onion  
- Wazuh  
- SQL Server  
- Rufus (ISO deployment)  

---

## Risks & Mitigations

| Risk | Mitigation |
|------|------------|
| Hardware failure | Document configs; maintain rebuild procedures |
| Scope creep | Team approval required for any changes |
| Uneven workload | Clear ownership of deliverables |
| Red Team damage | VM snapshots + recovery plan |
| Team availability | Keep documentation current for handoff |
| Misconfigured monitoring tools | Early test exercises to validate alerting |

---

## System Topology
*(Insert your network diagram here)*

---

## Platform & OS Details

| Name | OS | Domain | Role | Physical/Virtual | IP |
|------|----|--------|------|------------------|----|
| WINSERVFF | Windows Server 2025 | Fortfaux.local | Domain Controller | Physical | 192.168.1.10 |
| WINSERVFF (Backup) | Windows Server 2025 | Fortfaux.local | Backup Server | Virtual | 192.168.1.x |
| WindowsClientFF | Windows 11 | Fortfaux.local | Security Monitor | Physical | 192.168.1.x |
| Wazuh Manager | Ubuntu | Local | Wazuh Manager | Virtual | 192.168.1.115 |
| Security Onion | Security Onion | Local | Monitoring | Virtual | 192.168.1.60 |
| StudentClientFF | Windows 11 | — | Security Testing | Physical | 192.168.1.x |

---

## Highlights (Quick Summary)
- Led a 4‑person team through planning, deployment, and testing  
- Built a fully functional educational‑center‑style network  
- Deployed Security Onion + Wazuh for monitoring and alerting  
- Conducted Red Team vs. Blue Team exercises  
- Produced full documentation, diagrams, and playbooks  

---

## What I Learned
- Coordinating a multi‑person technical project with clear ownership  
- Designing and deploying a real‑world network from the ground up 
- Implementing layered security and monitoring  
- Running structured offensive/defensive security exercises  
- Writing professional documentation and incident response procedures  

---

## Screenshots
Screenshots are stored in the `/screenshots` directory.

---

<div align="center">

[Back to Portfolio](https://github.com/fenndw)

</div>
