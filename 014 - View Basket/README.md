# View Another User's Shopping Basket 🛒

**Objective**: Access and view the shopping basket of another user by intercepting and modifying a request.

## Steps:

1. **Log in to the Admin Account**:

   - Begin by logging into the administrator account on the Juice Shop platform.

     ![alt text](image.png)

2. **Capture the Request with Burp Suite**:

   - Ensure Burp Suite is running and intercepting traffic.

     ![alt text](image-1.png)

   - Click on **'Your Basket'** within the Juice Shop to trigger the request for the basket contents.

     ![alt text](image-3.png)

   - Burp Suite will capture the request.

3. **Identify the Basket Request**:

   - In Burp Suite, forward each request until you see the following request:
     ```plaintext
     GET /rest/basket/1 HTTP/1.1
     ```
   - The number `1` after `/basket/` represents your current user ID.

     ![alt text](image-2.png)

4. **Modify the User ID**:

   - Change the `1` to another number, such as `2`, in the request URL:
     ```plaintext
     GET /rest/basket/2 HTTP/1.1
     ```
   - Forward the modified request in Burp Suite.

   ![alt text](image-4.png)

5. **View the Other User's Basket**:

   - The response should now display the contents of User ID `2`'s basket.
   - You can repeat this process with different user IDs to view their baskets, provided those users have items in their baskets.

     ![alt text](image-5.png)
