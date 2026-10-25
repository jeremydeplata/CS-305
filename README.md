# CS-305
**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

Artemis Financial is a company that offers their clients advice on how they can save money for their future. Whether that be saving for retirement or investing and insurance. The goal for Artemis was to increase the security of their software application. I was able to help find flaws and make changes to better secure their application.


**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**

I found some weak points in the application using OWASP Dependency-Check. I inspected the code for the application as well to find better ways of securing the application. Having secure code can allow for your application to be protected from hackers and help keep private information private. As well, if you have a secure program you are more likely to gain trust from your customers.


**Which part of the vulnerability assessment was challenging or helpful to you?**

I found the OWASP Dependency-Check plugin a little hard to work with. It took a bit of time to get everything set up right when using it through Maven to run a scan. After that it was nice to see how many vulnerabilities can be found in your application's dependencies. Even if your application is running fine.


**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

To further improve my security I set up HTTPS by creating a self-signed certificate using RSA and then created a checksum using SHA-256. By doing this I was able to secure the communication and allow for data integrity checks. I would also use OWASP Dependency-Check and look through the code of my application to see what vulnerabilities I need to fix.


**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

Once I had my application updated I ran it through Eclipse and checked my console for any errors. I then tested the application in my browser to see if HTTPS and the checksum were working. I ran OWASP Dependency-Check and scanned my application's dependencies for vulnerabilities. There were 295 vulnerabilities found across 16 dependencies. This shows that there is still room for improvement when it comes to security.


**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

Some of the programs I used during this process were Eclipse, Maven, Java Keytool, and OWASP Dependency-Check. It's always good to know how to make your own certificates and set up HTTPS for other applications you may build. Testing your software after updating and checking your dependencies are things you should always do.


**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

I would present my finished Practices for Secure Software Report. I made many changes to the Artemis Financial application to make it more secure. From generating a certificate to implementing SHA-256. Having HTTPS and running Dependency-Check. I feel that this is a good example of me finding vulnerabilities and modifying an application. Then seeing if my changes took effect.

