# CS-305


Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their patrons. The company desires to modernize its operations and implement and apply the most current and effective software security. 

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

One of the main vulnerabilities was having the CA password shown in plain text in the code. It is important to code securely because errors can jeopardize the security of an entire company.

What about the process of working through the vulnerability assessment did you find challenging or helpful?

The process of implementing a checksum where plain text was encrypted was what I found the most challenging, but it was also what I enjoyed the most.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation technique?

To increase the layers of security, first plain text was encrypted, a CA was used to implement a secure connection between the client and the server and lastly, vulnerabilities were identified and a plan was proposed to correct them.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

The application was ran to ensure it was functional, and it was checked that the output was the same as expected. To ensure no new vulnerabilities were added, a dependency check was ran before and after refactoring the code.


What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

I found it useful to use Maven Dependency Checks to identify vulnerabilities.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would want to showcase my ability to identify vulnerabilities and propose mitigation plans as well as implement solutions.

