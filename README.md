<h1>Brute-force attack(pentest report)</h1>



<h2>Description</h2>In this security assessment, I successfully executed a targeted brute force attack on the application's login functionality using Burp Suite and a carefully curated list of dictionary passwords. This endeavor uncovered a critical security vulnerability, granting unauthorized access to the admin account by successfully pinpointing the correct password. Leveraging Burp Suite's Intruder tool, I meticulously cycled through a series of common passwords, systematically probing and ultimately compromising the admin login. The implications of this attack extend to users, web app owners, and the compromised data, posing a substantial security risk.
To recreate the attack, I intercepted the login request with Burp Suite Proxy, configuring the Intruder tool for a dictionary attack on the admin login. Employing a list of potentially weak passwords from a file named "500 worst passwords," I systematically and successfully identified the admin password through the brute force assault. To bolster the application's security and thwart future brute force attacks, I recommend implementing robust countermeasures such as account lockout mechanisms, stringent password policies, and the adoption of multi-factor authentication. These proactive measures will fortify the application's defenses and ensure a resilient security posture against such threats. #SecurityAssessment #BruteForceAttack #Cybersecurity 💻🔐<br />


<h2>Tools used/h2>

- <b>BurpSuite</b> 
- <b>500worsepasswords.list </b>


<h2>Report Walkthrough:</h2>

<p align="center">
Brute force report introduction: <br/>
<img src="https://i.ibb.co/DbBLBRB/Picturebrute1.jpg"/>
<br />
<br />
used Burpsuite with the attack list:  <br/>
<img src="https://i.ibb.co/Ky51MQd/Picturebrute2.jpg" alt="Picturebrute2"/>
<br />
<br />
Vulnerability remediation: <br/>
<img src="https://i.ibb.co/fppbGHf/Picturebrute3.jpg"/>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
