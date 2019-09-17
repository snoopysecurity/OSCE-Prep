# OSCE PREP Layout

This repository contains a list of freely availiable resources that can be used as a pre-requisite before enrolling in Offensive Security's [Cracking the Perimeter (CTP)](https://www.offensive-security.com/information-security-training/cracking-the-perimeter/) course and [OSCE](https://www.offensive-security.com/information-security-certifications/osce-offensive-security-certified-expert/) certification.


The following table shows notes, courses, challenges, and tutorials taken in preparation for the OSCE.

### Web Application Security

| Order | Name | Type | Link |
|--- | ----- | ----- | --- |
| 1 | PayloadsAllTheThings Directory Traversal CheatSheet | CheatSheet | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Directory%20Traversal |
| 2 | PayloadsAllTheThings XSS CheatSheet | CheatSheet | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSS%20Injection |
| 3 | XSS Payloads | Payloads | http://www.xss-payloads.com/ |
| 4 | XSS to Domain Admin | Webinar | https://www.elearnsecurity.com/resources/webinar_video/xss-to-domain-admin/ |


### Anti Detection

| Order | Name | Type | Link |
|--- | ----- | ----- | --- |
| 1 | Backdooring PE Files - Part 1 | Blog | http://sector876.blogspot.co.uk/2013/03/backdooring-pe-files-part-1.html |
| 2 | Backdooring PE Files - Part 2 | Blog | http://sector876.blogspot.co.uk/2013/03/backdooring-pe-files-part-2.html |
| 3 | Backdooring Windows EXEs for Fun and Profit | Blog | http://ly0n.me/2015/07/09/backdooring-windows-exes-for-fun-and-profit-part-1/ |
| 4 | Art of Anti Detection – 1 | Paper | https://www.exploit-db.com/docs/40900.pdf |
| 5 | Art of Anti Detection – 2 | Paper | https://www.exploit-db.com/docs/41129.pdf |
| 6 | Art of Anti Detection – 2 | Paper | https://www.exploit-db.com/docs/41129.pdf |
| 7 | Art of Anti Detection – 1 Blog | Blog | https://pentest.blog/art-of-anti-detection-1-introduction-to-av-detection-techniques/ |
| 8 | Art of Anti Detection – 2 Blog | Blog | https://pentest.blog/art-of-anti-detection-2-pe-backdoor-manufacturing/  |
| 9 | Art of Anti Detection – 3 Blog | Blog | https://pentest.blog/art-of-anti-detection-3-shellcode-alchemy/  |
| 10 | Art of Anti Detection – 4 Blog | Blog | https://pentest.blog/art-of-anti-detection-4-self-defense/   |


### Assembly Language

| Order | Name | Type | Link |
|--- | ----- | ----- | --- |
| 1 | Skullsecurity Assembly Language Wiki | Blog | https://wiki.skullsecurity.org/index.php?title=Assembly |
| 2 | Sensepost A Crash Course in x86 Assembly for Reverse Engineers | Paper | https://sensepost.com/blogstatic/2014/01/SensePost_crash_course_in_x86_assembly-.pdf |
| 3 | SecurityTube Windows Assembly Language Megaprimer | Videos | http://www.securitytube.net/groups?operation=view&groupId=6 |


### Exploit Development
| Order | Name | Type | Link |
|--- | ----- | ----- | --- |
| 1 | Corelan Exploit Writing Tutorial part 1: Stack Based Overflows | http://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/ | 
| 2 | Corelan Exploit Writing Tutorial part 2: Stack Based Overflows | jumping to shellcode | http://www.corelan.be/Writing/index.php/2009/07/23/writing-buffer-overflow-exploits-a-quick-and-basic-tutorial-part-2/ | 
| 3 | Corelan Exploit Writing Tutorial part 3: SEH Based Exploits | http://www.corelan.be/Writing/index.php/2009/07/25/writing-buffer-overflow-exploits-a-quick-and-basic-tutorial-part-3-seh/ | 
| 4 | Corelan Exploit Writing Tutorial part 3b: SEH Based Exploits | just another example | http://www.corelan.be/index.php/2009/07/28/seh-based-exploit-writing-tutorial-continued-just-another-example-part-3b/ | 
| 5 | Corelan Exploit Writing Tutorial part 4: From Exploit to Metasploit | The basics | http://www.corelan.be/index.php/2009/08/12/exploit-writing-tutorials-part-4-from-exploit-to-metasploit-the-basics/ | 
| 6 | Corelan Exploit Writing Tutorial part 5: How debugger modules & plugins can speed up basic exploit development | http://www.corelan.be/index.php/2009/09/05/exploit-writing-tutorial-part-5-how-debugger-modules-plugins-can-speed-up-basic-exploit-development/ | 
| 7 | Corelan Exploit Writing Tutorial part 6: Bypassing Stack Cookies, SafeSeh, SEHOP, HW DEP and ASLR | http://www.corelan.be/index.php/2009/09/21/exploit-writing-tutorial-part-6-bypassing-stack-cookies-safeseh-hw-dep-and-aslr/ | 
| 8 | Corelan Exploit Writing Tutorial part 7: Unicode | from 0x00410041 to calc | http://www.corelan.be/index.php/2009/11/06/exploit-writing-tutorial-part-7-unicode-from-0x00410041-to-calc/ | 
| 9 | Corelan Exploit Writing Tutorial part 8: Win32 Egg Hunting | http://www.corelan.be/index.php/2010/01/09/exploit-writing-tutorial-part-8-win32-egg-hunting/ | 
| 10 | Corelan Exploit Writing Tutorial part 9: Introduction to Win32 shellcoding | http://www.corelan.be/index.php/2010/02/25/exploit-writing-tutorial-part-9-introduction-to-win32-shellcoding/ | 





## Post Prep Breakdown

Having completed the course, below is everything done in regards to prep before the exam. If you have not taken the AWAE and are considering taking it definitely do everything shown above, and read the source! I have provided README's in each directory and source code so you can see what I did. I cannot share extra miles .... so those will not be within the repository. Best of luck!

- Complete all extra miles! I know some are harder than others but push through (one took me 8 days alone).
- Be comfortable using every debugger shown within the course.
- Understand Object Oriented Languages taught throughout the course. No need to be a master in each language, but be able to code something fast using existing libs.
- Be comfortable crafting a full POC (as done throughout the entire course)
- Look for vulnerabilities ;)

This may not seem like much, but it's what I did for prep. My best advice is DO NOT OVERTHINK things and don't rush through it. It took me 2 attempts when it should have taken one, I was jumping around not documenting enough what I was trying (It's easy to create your own rabbit holes...). Slow down you have 48 hours!
