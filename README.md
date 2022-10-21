# Dat250Social-Insecurity
**Project1

I used OWASP ZAP to uncover vulnerabilities on the web application and have performed some configuration before performing scaning.
I begun by setting up local proxy in OWASP and enable some OWASP extensions.Then I set sup the local proxy in my browser to mach with the one I craeted in OWASP.

Then I copied the Dynamic SSL certificate from OWASP for the proper work of proxy in my browser and imporetd it in to my browser so that they work in harmony.

Bu using OWASP ZAP built in functionalities, I have found around 25 Vulnerabilities/Alerts (as seen on Vulnerabilities.jpg), which we can use to attack the web application.

After the scanning I tried to perform brute force attack and have got some payloads, which we can see on the attched pictures. As a result I have managed to get a user name and password see picture (Attack result 04.jpg).

