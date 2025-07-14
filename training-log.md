Michael's Training Projects from Tryhackme
Offensive Security Intro - ethical hacking: identify potential vulnerabilities - Red Team

Exercise 1: Fake Bank Hacking
- use "dirb" to find hidden URLs with brute-force: dirb uses a list of potentia page names and tests them one by one to see if they exist innthe website.
- this must be executed in a Virtual Machine - also known as a terminal
- the command "dirb" uses a wordlist that contains many common filenames. 
I found two matches: images and bank-deposits
I entered this into the browser's address bar - this pulled up the admin portal where I was able to select the account and add $2000. 
Result: This exercise highlighted the vulnerability of using common file names within a secure URL. 

Defensive Security Intro - ethical hacking: identify potential vulnerabilities -  Blue Team stuff
