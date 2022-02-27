# Software-Security

Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their patrons. They are looking to modernize its operations and implement and apply the most current and effective software security for their custom software. They have a public web interface and needs to protect their client data and financial information. 

I believe that I was able to effectively work through each of the vulnerabilities and determine the course of action needed to address them. It was also very important to code securely as to not add any other new vulnerabilities to the software. If software security is handled properly and given the extreme attention it deserves then the client can operate their business smoothly and can offer their customer a sense of comfort knowing that their data is safe. 

I found it more time consuming than challenging to look through each vulnerability listed in the dependency check. Most were fixed with software updates, but it still took a fair amount of time to inspect each one. 

I approached the need to increase layers of security one step at a time. I was able to create my own self-signed certificate using the Java Keytool which allowed for secure HTTPS connection. From there I deployed and implemented the encryption algorithm cipher to the software application. To verify this, I used a checksum which confirmed the HTTPS connection and the functionality of the cipher. I scanned the code for vulnerabilities and updated the Spring Boot Release version. From there I ran a test on the refactored code with the dependency check tool. This dependency check showed that no additional vulnerabilities were added from my refactored code, and many were fixed from the updated version of the Spring Boot Release. To ensure that the security stays maintained I recommend regular updates to all the software that is used. These updates will fix any new vulnerabilities that may be found and will make sure that Artemis and their clients’ data remains safe and secure. 

I found these tools and resources I used with Artemis Financial to be very effective and useful. I plan to add them to my tool box for future assignments and tasks. 

I think my successful deployment of an encryption algorithm cipher is a very useful and practical skill that I would use to demonstrate my skills and experience. 
