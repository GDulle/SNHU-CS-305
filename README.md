# SNHU-CS-305

**Who was the client? What issue did they want addressed?**<br />
The client, Artemis Financial, is a financial consulting company that wanted to create an app for their clients. As a fianancial institutuion they were required by the PCI_DSS and the Graham-Leach-Bliley act to have all client data to be protected. Therefore the application that they were developing needed data encryption, secure communication and a secure application in order to provide services to their clients.

**What did you do particularly well in identifying their software securiuty vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall wellbeing?**
In this project I feel like my addition of encryption went very well, I enjoyed doing research into the different algorithyms available today and adding SHA-3 to this code went very smoothly. It's important to code securely as this is the groundwork the rest fo the application is built around, it doesn't matter if the strongest encryption is used, a well trusted certificate is in place, and all dependencies that are incldued in an application are without vulnerabilities if there's no input validation and a malicious party is able to get into the application by overloading a input. Software security can help to ensure that a company does not lose time, money, or other resources in having to deal with a compromised system, it also helps to protect a company's reputation and can lead to an increase in business in the future.

**What about the process of working through the vulnerability assessment did you find challenging or helpful?**
I found the dependency check tool incredibly helpful as it was able to quickly check what vulnerabilities had been found in the code that was bing used from the dependencies included in the code. This makes it much easier to address any issues that can arrise from using open source code.

**How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?**
By adding a controller to my RESTful API as well as the application of encryption this added several additional layers of security ofver what had been in place. In the future using penetration testing would further find vulnerabilities in a project so that they may be addressed.

**How did you ensure the code and software application were funcitonal and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**
AS I completed each step of my refactoring I would run the code and debug any issues that arose from these. I checked for vulnerabilities by running a vulnerability test after suppressing the previously found vulnerabilities to see if any new issues had been added.

**What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?**
After running into issues with my hash function when I tried something new, I looked to stack overflow to see how others had approached the issues I was running into. This has been a helpful tool so far in my work so far and proved to be helpful again. 

**What from this particular assignment might you wnat to showcase to a future employer?**
After solving the issues with my hash function I do think this is one of the most helpful things that I have learned, encryption is an important part of many web based applications these days, so knowing how to put encryption in place seems to be an important skill.
