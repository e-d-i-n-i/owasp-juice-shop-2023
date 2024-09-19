# Forged Feedback 📝

**Objective:**

Post feedback using another user's name.

## Steps to Complete:

1. **Turn Off Interception:**

   - Disable Burp Suite interception and turn off Burp in FoxyProxy.

2. **Log In:**

   - Log into your account on the website.

3. **Access Feedback Page:**

   - Navigate to the **Customer Feedback** page.
   - Fill in the comment and CAPTCHA fields.

4. **Enable Interception:**

   - Before hitting **Submit**, turn on interception in Burp Suite and enable Burp on FoxyProxy.

5. **Submit the Feedback:**

   - Hit **Submit** and capture the request in Burp Suite.

6. **Modify the Email:**

   - Inspect the captured request.
   - Change the email in the request to the email of the user for whom you want to post feedback.

7. **Intercept the Response:**

   - Right-click the captured request, hover over **Do intercept**, and select **Response to this request**.
   - Click the **Forward** button.

8. **Verify Success:**
   - A status code "2" will indicate a successful submission.
   - Click **Forward** again to complete the process.

## Completion:

After modifying and forwarding the request, you will have posted feedback in another user's name, completing the challenge.
