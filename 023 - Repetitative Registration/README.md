# Repetitive Registration Challenge 🔄

## Objective

The goal of this challenge is to bypass the **Don't Repeat Yourself (DRY)** principle by submitting the same registration information multiple times, which exposes potential vulnerabilities related to repetitive actions in the registration process.

## Instructions

1. Go to the **registration** page on OWASP Juice Shop.
2. Create a new account by filling in the email, password, and other required fields.
3. Once the registration is successful, repeat the process using the **exact same information** (email, password, and other fields) at least twice or more.
4. After the second registration, the challenge will be marked as completed, and you'll see the green flag.

## Description

This challenge demonstrates how an application might fail to enforce proper validation or checks for duplicate registrations. By allowing the same user to register with identical details multiple times, it highlights the importance of enforcing unique constraints, especially in user management systems.
