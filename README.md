# Phish-Catcher
<p>
  Cyber security confronts a tremendous challenge of maintaining the
confidentiality and integrity of user’s private information such as password and
PIN code. Billions of users are exposed daily to fake login pages requesting
secret information. There are many ways to trick a user to visit a web page such
as, phishing mails, tempting advertisements, click-jacking, malware, SQL
injection, session hijacking, man-in-the-middle, denial of service and cross-site
scripting attacks. Web spoofing or phishing is an electronic trick in which the
attacker constructs a malicious copy of a legitimate web page and request users’
private information such as password. To counter such exploits, researchers
have proposed several security strategies but they face latency and accuracy
issues. To overcome such issues, we propose and develop client-side defence
mechanism based on machine learning techniques to detect spoofed web pages
and protect users from phishing attacks.<br> <br> As a proof of concept, a Google Chrome
extension dubbed as Phish Catcher, is developed that implements our machine
learning algorithm that classifies a URL as suspicious or trustful. The algorithm
takes four different types of web features as input and then random forest
classifier decides whether a login web page is spoofed or not. To assess the
accuracy and precision of the extension, multiple experiments were carried on
real web applications. The experimental results show remarkable accuracy of
98.5% and precision as 98.5% from the trials performed on 400 classified
phished and 400 legitimate URLs. Furthermore, to measure the latency of our
tool, we performed experiments over forty phished URLs. The average recorded
response time of Phish Catcher was just 62.5 milliseconds. 

</p>
