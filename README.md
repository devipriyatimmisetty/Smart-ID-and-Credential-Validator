# Smart-ID-and-Credential-Validator
Project Objective
The goal of this project is to validate whether a student's registration details meet the university’s predefined format and security rules.
Inputs Taken
The system accepts four inputs from the user:
Student ID
Email ID
Password
Referral Code
Student ID Validation
The Student ID must follow the format CSE-XXX, where:
It must start with CSE-
The last three characters must be digits
Email Validation
The email must:
Contain exactly one @ and one .
Not start or end with @
End with .edu
Password Validation
The password must:
Be at least 8 characters long
Start with an uppercase letter
Contain at least one digit (0–9)
Referral Code Validation
The referral code must:
Be exactly 6 characters
Start with REF
Have two digits after REF
End with @
Logic Used
The program uses:
String indexing
String functions like isdigit() and count()
Nested if–else conditions
No loops, no lists, and no regular expressions
Final Output
If all conditions are satisfied, the program prints:
APPROVED
Otherwise, it prints:
REJECTED
Use Case
This system can be used in student portals, university registration systems, and hackathon validation modules to ensure only valid credentials are accepted.
