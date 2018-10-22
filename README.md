# week8_assign
# Project 8 - Pentesting Live Targets

Time spent: 12 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: <img src="my_gif_walkthrough_url" width="800">

Session Hijacking
I had two browsers, one logined in as the victim and looked at my session ID, copied and pasted the victims session into the attackers unloged session and now the attacker had access to the staff area.

Vulnerability #2: <img src="my_gif_walkthrough_url" width="800">

SQL injection
I went to a salesperson and added ' OR SLEEP(5)=0--' to the url and after 5 seconds it changed to another person but the ID remained the same.

## Green

Vulnerability #1: <img src="my_gif_walkthrough_url" width="800">

Cross-Site Scripting
I went to the feedback area and posted a comment with an alert script. I then logged into the staff area and checked the feedback and there was the alert.

Vulnerability #2: <img src="my_gif_walkthrough_url" width="800">


## Red

Vulnerability #1: <img src="my_gif_walkthrough_url" width="800">

Insecure Direct Object Reference
I clicked a salesperson made public and changed the ID in the URL to a person I knew was not supposed to be made public.

Vulnerability #2: <img src="my_gif_walkthrough_url" width="800">



## Notes

Describe any challenges encountered while doing the work
