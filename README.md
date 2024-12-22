The client for the two projects within this repository was Artemis Financial. They are a financial services company that contains a database with sensitive customer data, including financial transactions that should be kept secure.
The company wanted me to address issues with identifying vulnerabilites, as well as mitigating them, that it had within its existing code base. Furthermore, Artemis wanted me to recommend an algorithm to be used for encrypting 
their data while it is at rest and in transit to a client. This algorithm needed to provide the highest security as well as comply with regional security regulations and standards.

As for my strengths in finding vulnerabilites, there are a few things that I feel I did well. I used dependency checkers and manual code inspection to find potential security risks in the provided code base. Several of the 
vulnerabilities found had simple solutions, which I provided to Artemis, such as updating out of date third party tools that fixed these vulnerabilities in later patches. I used secure coding practices in what I added to the 
code base, ensuring that I did not cause any new dependencies to occur.

The part of the vulnerability assessment to me that was the most difficult would be deciding which vulnerabilites could be suppressed when generating the report. I had to do a lot of research into what each vulnerability 
stated, and even though I feel confident that I put my best effort into deciding which vulnerabilities provided an actual risk, finding those that did not apply to the code base was difficult for me. I am sure that spending 
more time studying would help me get better at this.

I improved security layers within the code base by incorporating SHA-256 into the project, this would provide secure hash generation. I recommended updating dependencies to their latest versions where vulnerabilites were 
patched out. I applied input validation to my lines of code that would aid in preventing injections occuring.

I made sure that the code and software application were functional by testing the code myself. To check to see if I introduced new vulnerabilites I generated a new report and compared it with the original report.

Coding practices that I learned form this assignment that would be helpful in the future is integrating Maven into my projects to test my code for vulnerabilities. Anything that I work on in the future that would require 
sensitive data will benefit from this entire course, as it not only gave me tools to make sure my code is more secure, it also introduced me to how serious of a threat malicious sources are and how I could quickly loose 
trust with my consumers should I not take this seriously.

From these assignments, I believe I could show future employers that I have an understanding of how to perform some entry-level software security tasks, and that I would be willing to add more to this and be a valuable 
asset to a team.
