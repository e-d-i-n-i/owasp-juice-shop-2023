# 💸 Payback Time Challenge

This challenge involves ordering a product in an unconventional way to generate money.

**Steps to solve the challenge:**

1. Select a product and add it to your basket.
2. Proceed to checkout.
3. Use Burp Suite to capture the checkout request.
4. Modify the request by changing the product quantity to `-1000`.
5. Disable Burp Suite interception and complete the remaining steps of the order process on the website.
6. Upon completing the order, you’ll successfully pass the challenge and receive the flag.

![alt text](<Screenshot 2024-09-09 082320.png>)
