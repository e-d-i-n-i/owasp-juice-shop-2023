# Weird Crypto Challenge 🔒

## Objective

The goal of this challenge is to notify the Juice Shop about the use of a cryptographic algorithm or library inappropriately within their codebase.

## Instructions

1. **Locate the Issue**:

   - Visit the Juice Shop GitHub repository: [OWASP Juice Shop GitHub Repo](https://github.com/juice-shop/juice-shop).
   - Navigate to the `lib` folder and open the file `insecurity.ts`: [insecurity.ts on GitHub](https://github.com/juice-shop/juice-shop/blob/master/lib/insecurity.ts).
   - Examine lines 42 and 43 in the file to identify the cryptographic algorithm used, which is "MD5 hash."

2. **Submit Feedback**:

   - Go to the Customer Feedback page in the Juice Shop application.
   - In the comment section, enter "MD5 Hash" to indicate the inappropriate use of this cryptographic algorithm.
   - Fill in any required fields and submit the feedback.

3. **Completion**:
   - After submitting the feedback, you will pass the challenge and receive the green flag.

## Description

This challenge highlights a common security issue involving outdated cryptographic algorithms. MD5, a widely known hashing algorithm, is considered insecure and should not be used for cryptographic purposes. By notifying the Juice Shop about this vulnerability through their feedback system, you are helping them improve their security practices.
