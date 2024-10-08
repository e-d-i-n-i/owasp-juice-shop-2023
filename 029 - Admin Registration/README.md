# Admin Registration Challenge 🛠️

## Objective

The goal of this challenge is to register a new user with administrator privileges by manipulating the registration request.

## Instructions

1. **Setup**:

   - Log out if you are currently logged in.
   - Ensure Burp Suite interception is turned on and enabled through FoxyProxy.

2. **Register a New User**:

   - Attempt to register as a new user on the Juice Shop application.

     ![alt text](image.png)

3. **Intercept the Request**:

   - As you submit the registration form, Burp Suite will intercept the request.
   - In Burp Suite, navigate to the **Proxy** tab and then the **Intercept** sub-tab to view the intercepted request.

     ![alt text](image-1.png)

4. **Modify the Request**:

   - Right-click on the intercepted request and select **Do intercept** > **Response to this request**.
   - Click the **Forward** button to view the response.

5. **Change User Role**:

   - In the response, you will see that the new user's role is set to "customer".

     ![alt text](image-2.png)

   - Now, repeat the registration process with different email but modify the role to "admin" in the request body inside brute suite.

     ![alt text](image-3.png)

     ![alt text](image-4.png)

     ![alt text](image-5.png)

6. **Forward the Modified Response**:

   - Forward the modified response to complete the registration with admin privileges.

     ![alt text](image-6.png)

7. **Completion**:

   - After making the changes and forwarding the request, you will have successfully registered with administrator privileges and will see the green flag.

   ![alt text](image-7.png)

## Description

This challenge demonstrates the importance of secure role management in web applications. By intercepting and modifying the registration request to grant admin privileges, you are highlighting how vulnerabilities in role assignment can be exploited. This exercise emphasizes the need for proper authorization checks and input validation in backend systems.
