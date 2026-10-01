# 12-Week Cybersecurity Daily Plan
### From Salesforce support role → offensive security fundamentals

**Rhythm:** ~1 hour on weekdays, 2–3 hours on weekends (~7–8 hrs/week). Adjust to your actual bandwidth — consistency matters more than hitting every box.

---

## Week 1 — Environment & Linux Intro
| Day | Task |
|---|---|
| Mon | Install VirtualBox + Kali Linux (or Ubuntu). Get comfortable booting/shutting down the VM. |
| Tue | TryHackMe: "Pre Security" path — intro rooms. |
| Wed | TryHackMe: Linux Fundamentals Part 1. |
| Thu | TryHackMe: Linux Fundamentals Part 2. |
| Fri | Create a GitHub repo for notes/write-ups. Document what you learned this week. |
| Sat | TryHackMe: Linux Fundamentals Part 3 (longer session). |
| Sun | Rest or light review — skim your notes, no new material. |

## Week 2 — Linux Deep Dive & Scripting Basics
| Day | Task |
|---|---|
| Mon | OverTheWire Bandit — levels 0–3. |
| Tue | Bandit — levels 4–7. |
| Wed | Bandit — levels 8–11. |
| Thu | Learn file permissions (chmod/chown) and processes (ps, top, kill). |
| Fri | Bandit — levels 12–15. |
| Sat | Bash scripting basics — write a script that automates a repetitive task. |
| Sun | Rest / catch-up on any missed Bandit levels. |

## Week 3 — Networking Fundamentals
| Day | Task |
|---|---|
| Mon | OSI model + TCP/IP basics (video + notes). |
| Tue | IP addressing and subnetting — do practice problems. |
| Wed | TryHackMe: "Network Fundamentals" room. |
| Thu | Install Wireshark. Capture traffic on your own machine, identify protocols. |
| Fri | Study common ports/services (21, 22, 23, 25, 53, 80, 443, 3389, etc.). |
| Sat | Wireshark deep dive: filter and inspect an HTTP session end-to-end. |
| Sun | Rest / review flashcards on ports and protocols. |

## Week 4 — Web Fundamentals
| Day | Task |
|---|---|
| Mon | How DNS resolution works, step by step. |
| Tue | HTTP vs HTTPS, TLS handshake basics. |
| Wed | Explore browser DevTools — Network tab, inspect requests/responses. |
| Thu | Practice with `curl`: GET/POST requests, headers, status codes. |
| Fri | TryHackMe: "HTTP in Detail" room (or similar). |
| Sat | Write a short summary post: "How a webpage loads" — your first blog/notes entry. |
| Sun | Rest. |

## Week 5 — Python for Security
| Day | Task |
|---|---|
| Mon | Python basics refresher — variables, loops, functions (skip if already comfortable). |
| Tue | Working with sockets in Python. |
| Wed | Build a simple port scanner (basic version). |
| Thu | Improve the port scanner — add threading or banner grabbing. |
| Fri | Write a Python script that sends HTTP requests and parses responses. |
| Sat | Polish and document your scripts on GitHub. |
| Sun | Rest. |

## Week 6 — Tools: Burp Suite & Nmap
| Day | Task |
|---|---|
| Mon | Install Burp Suite Community. Configure browser proxy. |
| Tue | Explore Burp's Proxy and Repeater tabs on a test site. |
| Wed | Learn cookies and sessions — inspect them live in Burp. |
| Thu | Install Nmap. Learn basic scan types (-sV, -sC, -A). |
| Fri | Run Nmap against a home lab target (e.g., a TryHackMe machine). |
| Sat | TryHackMe: "Nmap" room, full walkthrough. |
| Sun | Rest. |

## Week 7 — Checkpoint Week
| Day | Task |
|---|---|
| Mon | Start TryHackMe "Jr Penetration Tester" path — first room. |
| Tue | Continue the path. |
| Wed | Continue the path. |
| Thu | Continue the path. |
| Fri | Continue the path. |
| Sat | Write your first real write-up (a room or challenge you completed) and publish it. |
| Sun | Reflect: what's clicking, what's not. Adjust weeks 8–11 if needed. |

## Week 8 — SQL Injection
| Day | Task |
|---|---|
| Mon | PortSwigger Academy: SQLi — intro material + first 2 labs. |
| Tue | PortSwigger: SQLi labs 3–4. |
| Wed | PortSwigger: SQLi labs 5–6. |
| Thu | PortSwigger: SQLi labs 7–8. |
| Fri | Review: how SQLi is prevented (parameterized queries, ORMs). |
| Sat | Finish remaining SQLi labs. Write a short notes summary. |
| Sun | Rest. |

## Week 9 — Cross-Site Scripting (XSS)
| Day | Task |
|---|---|
| Mon | PortSwigger Academy: XSS — intro + first 2 labs. |
| Tue | PortSwigger: XSS labs 3–4. |
| Wed | PortSwigger: XSS labs 5–6. |
| Thu | PortSwigger: XSS labs 7–8. |
| Fri | Study CSP and output encoding as defenses. |
| Sat | Finish remaining XSS labs. Update your notes repo. |
| Sun | Rest. |

## Week 10 — Auth & Access Control
| Day | Task |
|---|---|
| Mon | PortSwigger: Authentication labs 1–2. |
| Tue | PortSwigger: Authentication labs 3–4. |
| Wed | PortSwigger: Access control labs 1–2 (IDOR focus). |
| Thu | PortSwigger: Access control labs 3–4 (privilege escalation). |
| Fri | Compare these bugs to Salesforce sharing rules / profile misconfigurations — write a short comparison note. |
| Sat | Finish remaining access control labs. |
| Sun | Rest. |

## Week 11 — Salesforce Security Lab
| Day | Task |
|---|---|
| Mon | Set up a free Salesforce Developer Edition org. |
| Tue | Write a small Apex class with a SOQL injection flaw (string concatenation). |
| Wed | Exploit your own flaw, then fix it with bind variables. |
| Thu | Test CRUD/FLS enforcement — build a case that fails without `with sharing`. |
| Fri | Read the OWASP Top 10 end to end, map each item to something you've now practiced. |
| Sat | Write a write-up: "Finding and fixing SOQL injection in Apex" — this is a strong portfolio piece. |
| Sun | Rest. |

## Week 12 — Review & Next Steps
| Day | Task |
|---|---|
| Mon | Review all notes from weeks 1–11. |
| Tue | Clean up and organize your GitHub notes repo. |
| Wed | Polish your two best write-ups for public sharing (LinkedIn, blog, or GitHub). |
| Thu | Research eJPT vs. Security+ — decide which to prep for next. |
| Fri | Outline your Months 4–6 plan based on what you enjoyed most. |
| Sat | Long session: start the first module of whichever cert you chose. |
| Sun | Reflect on the 12 weeks — what surprised you, what you want more of. |

---

### Notes
- Missing a day is fine — don't try to "catch up" by doubling up; just continue the schedule.
- If a week's material feels too easy or too hard, shift pace rather than forcing the calendar.
- Every write-up you publish, however rough, is worth more than another badge or certificate.
