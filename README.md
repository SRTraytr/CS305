# CS305
Artemis Financial Practices for Secure Software Report

    Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  The Client was Artemis Financial. The company was creating a program based on the Spring platform. Artemis Financial needed secure communication over HTTPS. 
    
    What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I feel I did well in choosing a cipher based on the client's needs. 
    
    What part of the vulnerability assessment was challenging or helpful to you?
I had some difficulty suppressing false positives in the maven assessment, it took a few tries and editing the .pom file to get the changes to stick. 
    
    How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
    I increased security by creating a checksum, using a self-signed certificate to use HTTPS, and using Maven to find vulnerabilities in the dependencies used in the program. 

    
    How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring the code, I completed another dependency check and manual review of the code. 

    
    What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The Maven dependency check tool will likely be helpful for future assignment. This course has also given me a better understanding of software security overall. 
    
    Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
    
I might use this assignment as an example of my ability to research and make recommendations for clients, this project also includes skill like creating a certificate with the key tool system and using Maven Dependency Check.
