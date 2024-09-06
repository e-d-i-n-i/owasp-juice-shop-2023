# Deluxe Fraud 🏆

**Objective:**

Obtain a Deluxe Membership without paying for it by manipulating the HTML code.

## Steps to Complete:

1. **Login:**

   - Log into your account or create a new account.

2. **Access Deluxe Membership Page:**

   - Navigate to this URL: `http://127.0.0.1:42000/scoreboard#/payment/deluxe`.

3. **Enable the Pay Button:**

   - The pay button is disabled on this page.
   - Right-click on the page and select **Inspect**.
   - Locate the **Pay** button in the HTML code and do the following:
     - Set the `disabled` attribute to `false` or remove the attribute.
     - If the class name contains `"mat-button-disabled"`, change it to `"mat-button-enabled"`.
   - Repeat the same steps for the **Continue** button.

4. **Setup Burp Suite:**

   - Make sure interception is enabled in Burp Suite.
   - Configure Burp Suite with FoxyProxy.

5. **Activate the Pay Button:**

   - After editing the HTML and enabling the buttons, click on the **Pay** button.
   - Capture the request in Burp Suite.

6. **Send to Repeater:**

   - Right-click the captured request and choose **Send to Repeater**.

7. **Modify and Send the Request:**
   - In the **Repeater** tab, locate the `paymentMode` field in the request.
   - Change the value of `paymentMode` to `"paid"`.
   - Click **Send** to submit the modified request.

## Completion:

Upon successfully changing the request and submitting it, you should receive a response indicating that the Deluxe Membership has been activated, completing the challenge.
