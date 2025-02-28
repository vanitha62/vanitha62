# Security Engineer Intern Task

## Overview

Security engineer would be helping and assisting us in making the platform more effective and secure against vulnerabilities. You will be using our platform along with the manual tools available in kali linux to carry out the given task.

## Task

- The task is very straightforward and open-ended, you have to conduct an in-depth pentest / security audit on https://testing.pinewheel.ai using the platform itself and manual tools available in kali-linux.
- You will be compiling a list of all the services and endpoints offered and test them for different vulnerabilities like SQL Injection, XSS, SSRF, SSTI, Prompt Injection, RCE, etc.
- You will keep track of all the tools you have used on kali-linux in a document in a format mentioned below.
- You will be using both the platform as well as kali alongside for conducting this audit.
- No need to manually keep track of the commands you’ve run on the platform after signing up.
- You can sign up for the platform from the above link using your email on which you have received this task.

## Deliverable

- Your deliverable for this task is a detailed pentest report giving an overview of the vulnerabilities found on the platform.
- Vulnerabilities should include both pre and post-auth services.
- Some bugs might also be categorised as vulnerabilities (a list of this also needs to be compiled)
- You can find example report here:

https://github.com/juliocesarfort/public-pentesting-reports/blob/master/CertiK/BHP_Mobile_Wallet_Penetration_Test_Report_01-09-2021.pdf

## Storing Format

- Store all the commands you have run on kali along with their output and your reason for invoking it in 1-2 lines.

```
command: nmap -Pn testing.pinewheel.ai
output: "OUTPUT"
reason: "REASON"

command: nmap -Pn testing.pinewheel.ai
output: "OUTPUT"
reason: "REASON"
```

- This will be used to review your thought process and effectiveness of the process apart from just the outcome.
