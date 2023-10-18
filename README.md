# CS-305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that develops financial plans for their clients. The plans include savings, retirement, investments, and insurance. They are looking to modernize their operations to include more current and effective software security. They wanted us to advise them on how to best protect their organization from external threats.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
The main thing I think I did very well with was doing research to see if any of the APIs that had vulnerabilities were ever updated to include fixes for the vulnerabilities known and for any that were also found in the updates. It's important to code securely because if we use APIs that have vulnerabilities being actively exploited, then we run the risk that someone learns of it and uses it to hack into the company and steal all the information stored in the system. It adds the benefit that any internal documentation that the company doesn't want to release stays secured inside the company instead of being leaked to the public to lower the company's reputation and to also lower the company's wellbeing.

What part of the vulnerability assessment was challenging or helpful to you?
I think the most challenging part of the assessment for me was the areas of security. The only reason is because, even after reading and re-reading the information, it just wouldn't click in my mind until I started just looking at the diagram and thinking of what a web application uses.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased security by including a hash function that encrypted the information to allow for anything sent to the server couldn't be decrypted easily or be plaintext for anyone to see. I see myself still using the OWASP dependency-check plugin to determine if there are any vulnerabilities in anything I use to ensure the system stays secured before releasing to live production/

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made certain the code and application were still functional and secure by running the dependency-check plugin before and after refactoring the code to ensure that any vunerabilities that were there before stayed but also ensured no new vulnerabilities were introduced in the process of refactoring.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The biggest tool that I used was the dependency-check plugin that was very helpful to me. I would definitely use the plugin in any furture assignments or task required of me through the rest of college and even in my future jobs.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show them how I documented each of the vulnerabilities shown through the dependency-check report and checked on how best to mitigate the issues to ensure the vulnerabilities were resolved.
