# Facebook Sign Up Testing

**Role:** QA Tester  
**Project Description:**  
Created and executed test scenarios for the Facebook Sign Up feature, ensuring all validations and user input requirements are properly handled.

## Highlights:
- Developed **Valid and Invalid Test Scenarios** covering:
  - Email field validation
  - Phone number input (with/without country code)
  - First and Last name (including short/long names and special character checks)
  - Age restrictions (13–18 and 18–120 years old)
  - Password validation
  - Gender selection
- Designed **high-level test scenarios** for quick review and execution
- Documented test scenarios in **structured Markdown format** for GitHub
- Ensured the system handles invalid inputs correctly and prevents registration with incorrect data

## Valid Test Scenarios:
1. Validate Sign Up with valid email address
2. Validate Sign Up with valid phone number
3. Validate Sign Up with valid Georgian First and Last name
4. Validate providing a short First or Last name (e.g., "ma-მა")
5. Validate providing a mobile number with and without country code (e.g., 592002304 and +995592002304)
6. Validate Sign Up with valid age in the range of 13 to 18 years old
7. Validate Sign Up with valid age in the range of 18 to 120 years old
8. Validate providing different values for gender

## Invalid Test Scenarios:
1. Validate leaving First name field empty
2. Validate leaving Last name field empty
3. Validate leaving email or phone number field empty
4. Validate leaving password field empty
5. Validate leaving gender field empty
6. Verify providing numbers or special characters in First name
7. Verify providing numbers or special characters in Last name
8. Verify providing a very short First name ("m")
9. Verify providing a very short Last name ("x")
10. Verify providing a very long First name (more than 50 characters)
11. Verify providing a very long Last name (more than 50 characters)
12. Verify providing a short mobile number ("1234")
13. Verify providing a long mobile number (more than 9 digits)
14. Verify providing a space in the mobile number
15. Verify copy/paste mobile number from other website or application
16. Verify adding an email with wrong format (e.g., "abc3423423")
17. Verify adding an email with a mistake in the format (e.g., "mari@gamil.com")
18. Validate a password with less than 6 characters (e.g., "A12#1")
19. Validate a password without letters (e.g., "1234@3$#")
20. Validate a password without numbers (e.g., "abc!@#$^&")
21. Validate a password without special characters (e.g., "avc322342v")
22. Validate providing a date of birth less than 13
23. Validate providing a date of birth more than 120

## Tools & Documentation:
- Manual testing
- Test scenarios documented in Markdown
- GitHub repository for version control and sharing
