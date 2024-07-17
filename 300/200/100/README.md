# 100 - Use Multipass with a Website that is not in the Multipass database

This scenario assumes the website (here: Linkwarden) is not in the Multipass database. It also assumes you already have an account with the website.

**NOTE**: Make sure there is a memory card slotted into the Multipass for storing the credentials.

On the computer:

- Enter your credentials on the login page of the website (here: https://cloud.linkwarden.app/login).
  ![mooltipass-connect-to-website-001](https://github.com/user-attachments/assets/1f702f5a-22a9-4f7e-b936-f460bea4715f)
- Click **Login**.
- A notification will alert you that a new credential is detected and that you can add it to Multipass.

On the Multipass:

- The Multipass will prompt:
  ```
  linkwarden.app
  Add New Credentials
  wvanheemstra@icloud.com
  ```
- The new credentials will be added automatically.

Next time, on the computer:

- Visit the login page of the website (here: https://cloud.linkwarden.app/login). **NOTE**: You do **not** have to enter the credentials at this moment.

On the Multipass:

- The Multipass will prompt:
  ```
  linkwarden.app
  Send Credentials For
  wvanheemstra@icloud.com
  ```
- Press the wheel to send the credentials to the login page.

On the computer:

- The credentials will have been sent by the Multipass to the login page, and you are automatically logged in!
  ![mooltipass-connect-to-website-002](https://github.com/user-attachments/assets/553acdf8-71a9-49ba-b309-dc1e4cb64b53)
