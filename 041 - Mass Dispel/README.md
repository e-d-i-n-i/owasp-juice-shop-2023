# 🚨 Mass Dispel Challenge

This challenge involves closing multiple notifications at once.

**Steps to solve the challenge:**

1. While viewing the notifications on the page, hold down the **Shift** key and close one of the notifications. This will close all notifications at once, completing the challenge.

**How we discovered this solution:**

1. Inspect the page where notifications appear.
2. Navigate to the **Sources** tab and open the `main.js` file.
3. Search for the term `"notifications"` in the code.
4. You'll discover that holding **Shift** while closing a notification will close all of them, helping you achieve the goal.

![alt text](<Screenshot 2024-09-09 064826.png>)
