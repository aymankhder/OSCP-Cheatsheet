# Offensive Security Cheatsheets... The Best Ever...
The goal of this repository is not to spoil or literally cheat on the OSCP Exam.  The real goal of this repository is to save you as much time as possible when enumerating and exploiting potential low hanging fruit.  It's very easy to get caught up in the weeds of debugging and troubleshooting broken payloads only to lose out on all your time to pass the exam.

You're on your own when the exploits start flying--I'll try to include potential tips and tricks you can try but it's up to you to fully understand the proper material before starting the exam.

## Start Here
| # | Step | Description |
| --- | --- | --- |
| 1 | `Discover` | Discover what's on the network |
| 2 | `Document` | Document your findings in CherryTree |
| 3 | `Select` | Select the specific cheatsheet for the box you are attacking |

-------------
## Discover
First, you must enumerate the attack surface of the box.  I have a curated list for each possible scenario you might run into.  The majority of recon is about following a checklist you are comfortable with, prioritizing your scanning efforts, and documenting you finding well.  Also get a high-level overview of the network and the available attack surface before getting into the weed with exploitation, evasion, and data exfiltration. 

**

**nmap**
| # | Command | Description |
| --- | --- | --- |
| 1 | `nmap -sn 10.0.0.0/24` | Quick SYN scan without looking for open ports  |

**Banner Grabbing**

**DNS Zone Transfer**

