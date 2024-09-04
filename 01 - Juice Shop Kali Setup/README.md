# Juice Shop Setup 💻

1. **Install Kali Linux VM**:

   - Begin by downloading a fresh Kali Linux VM from the [official Kali Linux website](https://www.kali.org/get-kali/#kali-virtual-machines).
   - Install and start the VM.
   - Log in to your Kali Linux environment.

2. **Update Repositories**:

   - Open the terminal.
   - Update the repository list by running:
     ```bash
     sudo apt update
     ```

3. **Install Juice Shop**:

   - After updating, install Juice Shop by running:
     ```bash
     sudo apt install juice-shop
     ```
   - For detailed instructions, refer to the [Kali Linux Juice Shop page](https://www.kali.org/tools/juice-shop/#:~:text=This%20package).

4. **Start and Stop Juice Shop Service**:

   - To start the Juice Shop service, run:
     ```bash
     sudo juice-shop -h
     ```
   - To stop the service, run:
     ```bash
     sudo juice-shop-stop -h
     ```

5. **Optional Video Tutorial**:
   - For a visual guide, you can follow this [video tutorial](https://youtu.be/QCxhywZecq8) to assist with the setup.
