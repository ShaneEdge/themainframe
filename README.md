Artemis Financial is a company that needed help securing its web-based software. Their goal was to ensure that public keys could be safely distributed and verified through checksum generation, and that sensitive client data remained protected over HTTPS. The client wanted us to address security weaknesses in the application and ensure that any software developed followed secure coding standards and protocols.

During the vulnerability assessment, I successfully identified known security issues in the code using the OWASP dependency-check tool. I recognized outdated or vulnerable libraries and generated reports that made it easy to see where changes were necessary. Addressing these vulnerabilities matters because insecure code can lead to serious data breaches. Secure software not only protects company and client data, but it also builds trust and helps ensure compliance with industry regulations, contributing directly to the business's reputation and operational reliability.

One of the more challenging parts of the vulnerability assessment was learning how to suppress false positives effectively without ignoring real risks. The step-by-step suppression process was helpful because it taught me how to fine-tune tools like the OWASP plugin to provide more accurate reports. It also helped me understand that not all flagged issues are critical—but still need to be reviewed.

To increase layers of security, I generated a secure hash using the SHA-256 algorithm for checksum verification, and I implemented SSL using a self-signed certificate to enable HTTPS for secure communication. In the future, I would continue using static code analysis tools like dependency-check, as well as dynamic testing when possible. I would also look into automated vulnerability scanners and integrate them into CI/CD pipelines.

To make sure the application was both functional and secure, I tested it thoroughly after refactoring. This included using REST endpoints to confirm the output of the checksum, checking HTTPS configuration in the browser, and re-running vulnerability scans after changes. These steps helped confirm that no new issues were introduced.

Some of the most useful tools and practices included the OWASP dependency-check plugin for Maven, using the Java Keytool to generate certificates, and following secure coding practices like not hard-coding passwords or using outdated libraries. These are all things I will use again.

If a future employer asked for an example of my work, I would show them the final dependency-check report with all vulnerabilities addressed or suppressed, my refactored checksum controller code, and a screenshot of the secure web browser showing HTTPS and the hash output. This would demonstrate not only my technical skills but also my attention to secure development practices from start to finish.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# themainframe
In these projects, we tackled structuring and managing course data for a Computer Science advising system. I approached this by focusing on data organization, user accessibility, and efficient implementation. Understanding data structures was crucial, impacting efficiency and ease of implementation.

Roadblocks came up, especially in choosing the best data structure for each task. Overcoming these challenges involved weighing trade-offs and considering factors like time complexity and memory usage. This work expanded my software design approach by highlighting modularity and scalability's importance.

The project emphasized code readability, maintainability, and adaptability. It pushed for clear naming, comments, and modular design, ensuring the code was understandable, facilitating maintenance and future modifications.



The DrivePass project was a system that allowed the company DrivePass to have a web-based application that can sign up and accept payments from new customers.  
The thing I did best was explain it in layman's terms to the nontechnical members of DrivePass
If I could change one thing I did it would be the UML class diagram. I was less confident in that diagram than the rest of them. 
I designed a forgiving system that allowed for wrong inputs without requiring a restart of the program. 
I approach software from the user's point of view. This allows for the most enjoyable programs to use and makes it easier to find things to improve on. 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

How do I interpret user needs and implement them into a program? How does creating “user stories” help with this?
How do I approach developing programs? What Agile processes do I hope to incorporate into my future development work?
What does it mean to be a good team member in software development?

I interpret user needs by first finding out what the desired outcome is. Next I will be sure to determine the requirements to complete this project. Then identifying which features and functionalities are most critical to the users and should be developed first.
User stories distill complex requirements into understandable and actionable statements. They keep the focus on delivering value to the end-user by framing features from the end-users point of view. They also keep everyone on the same page in terms of an end goal. 
To develop programs you need to start with planning and requirements gathering. This will give you a place to start. You want to understand what the end product needs to look like and how we will get there. Define what tools, technologies, and frameworks need to be used.
The development can start after you laid out what needs to be achieved. Integrate code changes frequently to detect issues early. This means testing frequently as we code as well as checking in with the client to ensure we do not have any change in goals. 
After developing and testing then we can deploy. Prepare production environments for software release. Continuously monitor performance and user feedback post-deployment. The final step is a never-ending one. The program needs to be maintained and always improved when possible.
Address any issues that arise after deployment. Some agile practices to help with this would be building software in small, manageable increments, allowing for frequent reassessment and adaptation. Also working in sprints to set deadlines for each task. Sprint planning and reviews are also needed to get everyone focused on the correct task and to maintain constant communication. 
Being a good team member in software development means more than being competent in your role. It also means being a good teammate as you would be on any team. Being there to support your teammates and listen to their struggles, making sure you inform teammates of your own struggles and also being professional. This can mean being on time every day, behaving courteously, and staying focused. 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
