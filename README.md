# password-checker

A truly secure way for you to check if the passwords you use in real life have ever been hacked.

This project makes you to securely check if your password has been pwned or hacked.
It uses **Pwned Passwords API** to get the passwords that have been leaked in the past using only the first five characters of the SHA1 generated password.

# How is it secure

Well the Troy Hunt's website uses the same technique as this project does i.e, Hash K-anonimity. Although if you are using the website to check Your password. I find it still not
secure because your password is still transmitting through the Internet.

# How does this project help in this issue

This project is just a single python file that helps us run locally. It uses the API of **Have I Been Pwned** website. Your computer needs to be connected to the Internet.
But your password will not be transmitted through the Internet

# How to use and run this file on your local computer

**Pre-requisites**:
-You should know how to use Power Shell(Windows) or Terminal(Mac).

You should copy the **checkmypass.py** file into your local computer.

1. Create a text file and input passwords using **Enter** key
2. Install Requests package **pip install requests**
3. Run **checkmypass.py** using Power Shell(Windows) or Terminal(Mac)
   -> Example: **python checkmypass.py passwordsToCheck.txt**
