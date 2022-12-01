# GraphicalPassword

User authentication is an important way to ensure the security of your cyber account. Although there are various authentication methods such as iris and fingerprint, passwords will be the main authentication method for the time being due to their low cost and ease of implementation. But this ease of implementation is also a factor which makes it less secure compared to other methods. We have tried to design a system, based on images and grids and to develop a new system with the same ease of implementation but with more security with respect to common attacks. We have incorporated the principles used in captcha and pass point methods and developed a new system altogether which is developed as a module and can be integrated with any existing portal or system.

## Safe from:
* <b>Brute Force Attacks</b><br>
After reaching max tries, the user will be notified via message through email. And the further authentication through the generic URL/website is disabled for that user account, instead, they have to use the link that will be sent by the company in the notification email. This also lets the legitimate user know about the adversary.

* <b>Phishing</b><br>
Since the adversary is made to believe that the password is a set of images, it’s not possible to make a fake page, since the adversary thinks he doesn’t know the images. Moreover, we restrict the user to one attempt and suggest the user to give a fake password every time so that he triggers the server to send and URL in email so that he can log in through the legitimate login page, and the adversary cannot send the URL to users from a legitimate server. However, when the adversary knows the technique this attack might be still possible.

* <b>Dictionary Attacks</b><br>
These types of attacks use a predefined set of combinations of values which may have been obtained from the personal information of the or may be completely random. Even though the images used at the time of registration can affect the password sequence chosen, but the images always permute in the grid from the database. Thus the occurrence of the same grid which was at the time of selecting the passwords.

* <b>Session Sniping</b><br>
These types of attacks make use of session hijacking tools to obtain active session cookies and cookies related to logging information which are generally stored in browsers’ cache memory as cookies. The image sequence is impossible to store in form of cookies in the browser as they are designed to store alphanumeric passwords and prevents this types of attacks.

* <b>Keyloggers</b><br>
Key-loggers secretly capture keystrokes and transfer, but if the spyware wants to track the mouse movements, it can be tracked, but the adversary wouldn’t know which part of the mouse event is actually the graphical password.

* <b>Shoulder Surfing</b><br>
Shoulder surfing is a type of social engineering technique used to obtain information such as personal identification numbers (PINs), passwords and other confidential data by looking over the victim's shoulder. The system we adopt is similar to the Phone pattern system. The pattern is invisible on the screen when the users draw it. This makes it incredibly tough for the adversary to see the images on the grid that the user clicks.


## Architecture:
<div align="center">
<img src="https://user-images.githubusercontent.com/70879718/173276628-d9733c9b-d61f-4677-89ca-8152e11721d2.png">
<!-- ![image](https://user-images.githubusercontent.com/70879718/173276628-d9733c9b-d61f-4677-89ca-8152e11721d2.png) -->
</div>
<br>

[![Made with Django](https://img.shields.io/badge/Made%20with-Django-092E20?style=for-the-badge&logo=Django&logoColor=092E20)](https://www.djangoproject.com/)
[![Made with Bootstrap](https://img.shields.io/badge/UI%20build%20with-Bootstrap-purple?style=for-the-badge&logo=Bootstrap)](https://getbootstrap.com/)

<br>

Cooked with <span style="color: #e25555;">&#9829;</span> by [WilsonVD](https://github.com/Wilson0406), [RishankP](https://github.com/RishankPratik) & [AnanthuM](https://github.com/Ananthu18)
