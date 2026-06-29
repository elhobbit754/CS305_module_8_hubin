* Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address? 
  * Artemis Financial is a firm that develops personalized financial plans for its customers. The company wanted to increase the
      security of its operations by adding a couple of extra layers of security to protect web UI that they already had.
* What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
  * I installed the owasp maven plugin to perform dependency check on the client's Java application. Coding securely is crucial 
  because compromising the codebase of an application could lead to major issues for the company. 
* Which part of the vulnerability assessment was challenging or helpful to you?
  * I had never really used the owasp maven plugin before this class. I am glad that I found something new for me to know about
  in my future projects.
* How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  * I added a self-generated SSL certificate and updated really old dependencies in pom.xml.
* How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  * I used a modern built-in Java API (MessageDigest) in order to generate checksum verification. I also made sure that the project's
  dependencies were upgraded as well.
* What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  * I am going to remember that there is a tool that analyzes dependencies and checks them against a database.
* Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  * I am not sure if such a small project could really be used to showcase coding skills to employers in 2026.
  It appears to me that something much bigger and more complex is needed to spark even a bit of an interest in potential employers.
