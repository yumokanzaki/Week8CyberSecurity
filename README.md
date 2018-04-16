# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

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

Vulnerability #1: REFER TO Week8Blue1 (For Image) Session Hijacking

For The first one you log in like normal and go to https://111.112.113.114/blue/public/hacktools/change_session_id.php (You IP will differ from this one)for the extention and copy the PHPSESSIONID. From there open a new browser and try going to the login returning to the Hack tools and paste the value of the copied PHPSESSIONID into the new one and change. Then go to the login and you'll be logged in without having to type in user and password

Vulnerability #2: REFER TO Week8Blue2 (For Image) SQL Injection

  You can change the extension of the value at the end of the sting of the URL to 'OR SLEEP(13)=0--' to manipulate a timer before rotating profiles. In this case it's 13 seconds.

## Green

Vulnerability #1: REFER TO Week8Green1 (For Image) User Enum

For the User enum the existing accounts are bold while non existant accounts are not.

Vulnerability #2: REFER TO Week8Green2 (For Image) XSS

For this one you simply go to the contact page then type in a name and email like normal but for the Comment insert <script>alert('Test');</script>

## Red

Vulnerability #1: REFER TO Week8Red1 (For Image)IDOR



Vulnerability #2: REFER TO Week8Red2 (For Image)CSRF



## Notes

Describe any challenges encountered while doing the work
