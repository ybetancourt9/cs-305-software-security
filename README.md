# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
The client is Artemis Financial which specializes in making custom financial plans for clients. They wanted to expand the functionality of their app to include
file verification to be able to transfer data safely. They wanted to make use of checksum to verify the integrity of the data since they deal with sensitive data
that needs to be valid and accurate.

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I was able to assess the vulnerabilities and implement a solution using an adequate and robust cipher suite to ensure data integrity which is was of the utmost importance to them.
In addition, I created a certificate to make use of https for authorization and encryption purposes ensuring session spoofing or hijacking were not a concern.
Securing code is paramount, especially for companies that deal with sensitive data since leaks could result in loss of money or reputation. It can even ruin people's livelihoods if personal details are
exposed to the public.

# Which part of the vulnerability assessment was challenging or helpful to you?
The assessment in itself was not particularly difficult. The issue was researching the different cipher suites and selecting what I believed to be the most appropriate for the client based on their
use case. For example, selecting between symmetric vs asymmetric encryption, key size, etc. There are so many options that it can be daunting to select one when so many seem to be be a good fit. OWASP was certainly a good resource to educate myself more on the matter and make a selection.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased the layers of security in two ways. The first layer had to do with the cipher suite to protect data integrity using a cipher suite. The second layer introduced a certificate to leverage https
ensuring that the connection was not susceptible to common vulnerabilites like man-in-the-middle attacks and improved trust between the client and their customers. In the future I would continue using OWASP as a resource to stay abreast on the latest practices and vulnerabilities when making crucial security decisions. I would also continue leveraging dependency checkers to make sure packages being used do not introduce vulnerabilites.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
When it came to the code, I tested it several times to ensure that the cipher suite was working as intended, primarily when it came to producing unique hashes every single time. When it came to the certificate,
the test was more straightforward. I made sure that the connection was shown as secure on the browser. I essentially ran the same test cases and ran the dependency checker to ensure new vulnerabilities had been
introduced.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The main resource I used was OWASP. I also used Java's documentation when researching cipher suites available. I was able to research different vulnerabilities and recommendations through their website. I also made use of the dependency checker to review possible vulnerabilities introduced by different packages and either fixed them or suppressed them if they were false positives.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I can show this assignment to future employers to demonstrate that I am capable of assessing critical vulnerabilities, and know how to research and implement solutions that are up to industry standards.
I can show them I have a good understanding of different types of encryptions and cipher suites, including the different types of encryption and tradeoffs with each solution. I can also demonstrate I understand
that data encryption is not enough, and that through the use of certificates I can ensure a connection is secure so a third party cannot intercept requests and potentially steal sensitive data.
