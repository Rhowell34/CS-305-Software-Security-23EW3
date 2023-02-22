# CS-305-Software-Security-23EW3
1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial needed us to help them address secure communications between their clients and the company itself. This secure communication and encryption also helped Artemis comply with government and financial institution regulations. If communications are not secured Artemis Financial may face fines and potential legal action which will also lead to a loss in consumer confidence. Artemis Financial also deals with large amounts of PII (personally identifiable information) such as names, bank accounts, social security numbers, date of birth, etc. The protection of this information is also federally regulated so secure communications are critical to consumer confidence in Artemis Financial.

2. What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?. 
I believe that I addressed the vulnerabilities in the correct manner as soon as they were found. I implemented secure API's very well as well as secure keys. The portion I struggled with was the certificate and getting the HTTPS to function properly. Coding securely protects clients from potential intrusions that may lead to monetary loss or loss of consumer confidence. Security protects the company from many potential bad actors such as hackers as well as helping them comply with federally mandated guidelines that could incur monetary or criminal punishment if neglected.

3. What part of the vulnerability assessment was challenging or helpful to you?
The most challenging part for me was the manual code review. I am still new to coding and don’t have enough experience to see flaws right away. This means it took me much longer to find the vulnerabilities. I believe with more experience I will become much more efficient though.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
The process I used to add secure layers to the software application was the use of the hash function. A secure RESTful API as well as a self-signed certificate and keystore. This provides a defense in depth strategy and provides the best layers of security possible for the Artemis Financial software application. We should also ensure that we run a dependency check on a routine basis to ensure that new threats do not propagate as well. The version of spring-boot should also be updated at the earliest time possible to ensure that the software application is running on the newest available software that is free of bugs. In the future I would still use the Maven dependencies check as a mitigation technique as well as all the layers of security mentioned above.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I reran the maven check multiple times after I refactored the code and tried to ensure there were no added vulnerabilities. I also updated to the latest possible versions of both the spring plugin as well as the dependency check.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I believe the maven dependency check will super helpful on future assignments as I dive deeper into the computer science program here at SNHU. Also, a focus on secure coding will be very important.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show that I am capable of developing self-signed keys as well as creating a certificate. I will also show them my ability to run a maven dependency check as well as updating it to remove false positives.
