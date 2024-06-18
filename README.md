NAME : KAMALESH BHANU DK

COMPANY : CODTECH IT SOLUTIONS

ID : CT08DS1750

DOMAIN : CYBER SECURITY AND ETHICAL HACKING

DURATION : 4 WEEKS

MENTOR : SRAVANI GOUNI


OVERVIEW OF THE PROJECT

Project : Password Strength Checker: Evaluating Length, Complexity, and Uniqueness.

Objective

The Password Strength Checker project is a Java-based tool designed to evaluate the strength of user-entered passwords. The tool analyzes various factors such as length, complexity, and uniqueness to provide a comprehensive assessment of password strength. The primary goal of this project is to help users create strong, secure passwords by offering feedback on the strength of their passwords and suggesting improvements if necessary.

Key Features

> Length Analysis:

The tool checks the length of the password and assigns a score based on its length. Longer passwords generally contribute to stronger password strength.

> Complexity Analysis:

The tool evaluates the complexity of the password by checking for the presence of uppercase letters, lowercase letters, digits, and special characters. Each of these elements adds to the complexity score, enhancing the password's security.

> Uniqueness Analysis:

The tool assesses the uniqueness of the password by counting the number of distinct characters. A higher number of unique characters indicates a more secure password.
Overall Strength Assessment:

Based on the combined scores from length, complexity, and uniqueness, the tool provides a final strength assessment, categorizing the password as "Very Strong," "Strong," "Moderate," or "Weak."

Code Explanation

> Main Method:

The main method handles user input by prompting the user to enter a password. It then calls the calculateStrength method to compute the strength score of the password and uses the getStrengthLevel method to determine the strength category based on the score.

> Calculate Strength Method:

This method evaluates the password based on three criteria: length, complexity, and uniqueness.
Length Score: Assigns a score based on the password's length, with longer passwords receiving higher scores.
Complexity Score: Analyzes the presence of different character types (uppercase, lowercase, digits, special characters) and increments the score for each type found.
Uniqueness Score: Counts the number of distinct characters in the password and assigns a score based on the count.
The total score is the sum of the length, complexity, and uniqueness scores.

> Get Strength Level Method:

This method translates the total score into a descriptive strength category. Scores are mapped to categories such as "Very Strong," "Strong," "Moderate," and "Weak," providing users with a clear understanding of their password's strength.

Usage

User Input:

The user is prompted to enter a password.

Output:

.![password](https://github.com/KAMALESH-BHANU/CODTECH-TASK1/assets/173052485/50e2d125-ec68-462d-ba77-c47b9cb0c0d9)

Strength Calculation:

The tool evaluates the password and calculates a strength score based on predefined criteria.

Technology Used:

The primary programming language used in the project is Java

Feedback:

The tool provides feedback on the password's strength, helping users understand how secure their password is and suggesting improvements if necessary.

Benefits

Security Improvement: Helps users create stronger passwords, thereby enhancing security.
User Education: Educates users about the factors that contribute to password strength.
Immediate Feedback: Provides instant feedback, enabling users to improve their passwords in real-time.

Conclusion

The Password Strength Checker project provides a useful and practical tool for users to evaluate and improve their password security. By focusing on length, complexity, and uniqueness, the tool offers a well-rounded assessment of password strength and encourages the creation of secure passwords. This project serves as a foundational example of how basic security principles can be implemented in a user-friendly application.

