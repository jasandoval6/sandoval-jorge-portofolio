# 🔐 CTF Cybersecurity Project — Buffer Overflow Challenge

**Technologies:** C, Python, Linux (Ubuntu), Auditd, Ghidra  
**Role:** Security Project Contributor (Buffer Overflow & Environment Setup)  
**Type:** Graduate Cybersecurity Project

---

## Overview
This project involved designing and implementing a stack-based buffer overflow challenge as part of a multi-stage Capture The Flag (CTF) exercise. 
The challenge required participants to analyze vulnerable C programs, extract memory-related information, and calculate exploit offsets within a controlled Linux environment.

My primary contributions focused on **buffer overflow analysis**, **challenge environment automation**, and **system-level monitoring** to support secure and traceable challenge execution.

---

## Key Contributions

### Buffer Overflow Challenge Design
- Contributed to the buffer overflow section of the CTF by analyzing vulnerable C programs and defining challenge logic requiring memory inspection and offset calculation.
- Supported challenge flow where participants must identify:
  - Buffer size
  - Buffer memory address
  - Base Pointer (EBP) address
- Designed the challenge to validate correct inputs and compute offsets dynamically, reinforcing exploitation fundamentals without requiring live shell access.

---

### Environment Setup & Automation (Python)
- Developed a Python-based startup script to automate environment setup on Ubuntu 20.04, ensuring consistency across challenge instances.
- Automated installation and configuration of required tools, including:
  - Ghidra (for static binary analysis)
  - Auditd (for system activity monitoring)
  - Wireshark and supporting dependencies
- Implemented scripted configuration to reduce setup errors and standardize participant environments.

---

### System Monitoring & Audit Logging
- Configured Auditd rules to track:
  - Execution of system commands
  - Access to challenge binaries and related files
  - Use of analysis tools such as Wireshark
- Implemented file-level monitoring to log read, write, and execution activity on challenge artifacts.
- Ensured visibility into participant interactions while maintaining a controlled and ethical testing environment.

---

## Buffer Overflow Walkthrough (High-Level)
Participants progressed through the challenge using the following approach:

1. Unlock access to challenge files using credentials obtained from previous stages.
2. Analyze vulnerable C binaries (e.g., `C5_1`, `C5_2`, `C5_3`) using tools such as Ghidra.
3. Identify critical memory details, including:
   - Buffer size
   - Buffer address
   - EBP address
4. Input the extracted values into the challenge program.
5. Receive calculated offset output upon successful analysis.

This structure emphasized **understanding memory layout and exploitation mechanics** rather than automated exploitation.

---

## Engineering Focus
Low-level programming • Memory analysis • Security fundamentals • Linux system configuration • Automation scripting • Ethical exploit design

*(Source code maintained in a private repository — technical walkthroughs and implementation details available upon request.)*
