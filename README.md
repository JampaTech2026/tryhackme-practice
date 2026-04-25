# tryhackme-practice
[JAMPA26 on TryHackMe](https://tryhackme.com/p/JAMPA26)

TryHackMe Room: Think Like a Hacker

**Path:** Introduction to Cyber Security → Offensive Security  
**Date Completed:** April 25, 2026  
**Difficulty:** Easy  

## 🎯 Objective

This room introduced offensive security and the attacker mindset. The goal was to understand how ethical hackers find weaknesses before real attackers can exploit them. The lab also included practice with finding hidden web pages and accessing an admin panel.

## 📚 What I Learned

### Task 1 — Think Like a Hacker

- Offensive security means ethical hacking or penetration testing.
- The goal is to find security weaknesses before malicious attackers do.
- Hackers think creatively about how systems can be misused.

### Task 2 — Starting the Lab

- Learned how to start a TryHackMe machine.
- Used the browser-based AttackBox.
- Learned how to identify and use the target IP address.

### Task 3 — Finding Hidden Pages

- Websites may have hidden pages that are not linked from the homepage.
- Tools such as **Gobuster** or **Dirb** can help discover hidden directories and pages.
- Example command:

```bash
gobuster dir -u http://TARGET_IP -w wordlist.txt

