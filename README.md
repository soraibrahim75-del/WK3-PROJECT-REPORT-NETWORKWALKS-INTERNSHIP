# WK3-PROJECT-REPORT-NETWORKWALKS-INTERNSHIP
Week 3: Cracking Locked PDFs
 
What this is
 
This is my Week 3 project for my cybersecurity training. The assignment was to break the passwords on locked PDF files.
 
I did everything from my Windows computer. For the first part, I used a downloaded version of John the Ripper. For the second part, I used the web tools provided by Networkwalks.
 
The targets: Locked PDF files
Where I did it: Windows PC
Tools used: John the Ripper (downloaded), Networkwalks Hash Calculator, Networkwalks Password Cracker. 
 
How I did it
 
You can't crack a PDF directly. You have to pull the password "hash" out of the file first. Once you have that hash, you can put it into a tool to find the password.
 
Method 1: John the Ripper
 
For the first target, I downloaded John the Ripper onto my Windows machine.
* The process: I extracted the hash from the PDF and pasted it into John the Ripper.
* Result: The program processed the hash and gave me the password. 
Method 2: Networkwalks Tools
 
For the second target, I used the Networkwalks web tools instead of downloading software.
* The process: First, I uploaded the locked PDF to the Networkwalks Hash Calculator to get the hash. (I had to use their calculator because I couldn't just use a regular online hash tool for this). Once the calculator gave me the new hash, I copied it and pasted it into the Networkwalks Password Cracker.
* Result: The Password Cracker successfully found the password. 
 
What I learned
1. Getting the hash is step one. You can't attack the PDF file itself. If you don't get the hash out first, the cracking tools won't work.
2. Different tools have different steps. With John the Ripper, I brought the hash to the software. With Networkwalks, I had to use their specific Hash Calculator to generate the right hash before I could put it into their Password Cracker.
3. Web tools are very straightforward. The Networkwalks tools were fast and easy to use right in the browser. I didn't have to worry about installing anything.
