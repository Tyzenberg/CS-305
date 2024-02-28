# CS-305
SNHU CS-305 Software Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is financial consulting company. They provide financial plans for their customers. They were looking to modernize their services and wanted support securing their API.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I added a hash function to their program which can be used as a digital signiture. I also self-certified to enable HTTPS.

What part of the vulnerability assessment was challenging or helpful to you?
The hardest part of the vulnerability assessment was trying to determine what wasn't a vulnerability. I see everything as being a vulnerability, but it felt like the assingments wanted to focus on a couple specifics. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Manual code review is the first layer of security. A static test is a good second check that contains a cumultive effort to prevent vulnerabilities. Vigorous and continous testing is the last layer of security I would recommend. This includes hiring white hackers and issuing bug bounty programs.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After making a change to the code, even minor, I would rerun the program as a java application and launch the local host to verify it was running. I also reran the static test after each change.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I bought the physical copy of the course material to go back and reference once in a while. I would also like to get better with the static tester. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would highlight the knowledge I gained in learning about encryption, it's flaws, and how to counteract those weaknesses. I started this course knowing of encrytption, but not quite what it was. While learning about it in this course, I started brainstorming ways to imrpove it and researching if any of those brainstorms had merit. This is when I discovered hybrid cryptosystems, using symmetrical encryption for data, but asymmetrical encryption for key sharing.
