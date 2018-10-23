# week8_assign
# Project 8 - Pentesting Live Targets

Time spent: 7 hours spent in total

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

Vulnerability #1: Session Hijacking

<img src="https://github.com/bnj111/week8_assign/blob/master/blue_session_hijack_2.gif" width="800">


I had two browsers, one logined in as the victim and looked at my session ID, copied and pasted the victims session into the attackers unloged session and now the attacker had access to the staff area.

Vulnerability #2: SQL injection

<img src="https://github.com/bnj111/week8_assign/blob/master/blue_sql_1.gif" width="800">

SQL injection
I went to a salesperson and added ' OR SLEEP(5)=0--' to the url and after 5 seconds it changed to another person but the ID remained the same.

## Green

Vulnerability #1: Cross-Site Scripting

<img src="https://github.com/bnj111/week8_assign/blob/master/green_css_1.gif" width="800">

I went to the feedback area and posted a comment with an alert script. I then logged into the staff area and checked the feedback and there was the alert.

Vulnerability #2: Username Enumeration
<img src="https://github.com/bnj111/week8_assign/blob/master/Green_user_2.gif" width="800">

This demonstrates that there is a Username Enumeration because it the login successful attempt gets bold when a user exists.

## Red

Vulnerability #1: Insecure Direct Object Reference

<img src="https://github.com/bnj111/week8_assign/blob/master/red_idor_1.gif" width="800">

I clicked a salesperson made public and changed the ID in the URL to a person I knew was not supposed to be made public.

Vulnerability #2: Cross-Site Request Forgery (CSRF)
<img src="https://github.com/bnj111/week8_assign/blob/master/red_csrf_2.gif" width="800">

This demostrates that someone can inject html code in the feedback area and perform cross site request forgery

