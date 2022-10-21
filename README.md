# Dat250Social-Insecurity
**Project1




 (For the respective OS in your computer)

Download page: https://www.virtualbox.org/wiki/Downloads

2.   Attacker machine- Kali Linux

Download page- https://www.kali.org/downloads/


My penetration testing is set up on Virtual Box as it allows me to create Virtual Machines inside the current OS.

To set up the working environment, the following programs need to be downloaded and installed:

1.  Oracle Virtual Box
2.  Attacker machine- Kali Linux
3.  Victim (vulnerable machine) social-insecurity web site.

I used OWASP ZAP to uncover vulnerabilities on the web application and have performed some configuration before performing scaning.

I begun by settings next to the Connection spot, then make sure it's set to Manual proxy configuration and enter 127.0.0.1 as the HTTP Proxy and 8080 as the Port.Then I set sup the local proxy in my browser to mach with the one I created in OWASP.

Then I copied the Dynamic SSL certificate from OWASP for the proper work of proxy in my browser and imporetd it in to my browser so that they work in harmony.
By using OWASP ZAP built in functionalities, I have found around 25 Vulnerabilities/Alerts (as seen on Vulnerabilities.jpg), which we can use to attack the web application.

After the scanning I tried to perform Fuzzer and brute force attack and have got some payloads, which we can see on the attched pictures. As a result I have managed to get a user name and password as seen picture (Attack result 04.jpg and OWASP Attack & Fuzz 03.jpg).

