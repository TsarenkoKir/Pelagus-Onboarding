
This code is for a webpage that allows users to connect their Pelagus Wallet directly from the browser. 

## Main Features:
There is a button labeled "Connect Pelagus Wallet". When you click this button, the webpage will try to connect to your Pelagus Wallet.
After clicking the button and successfully connecting to the wallet, the webpage will display your wallet's address. 
Initially, it says "Wallet Address: Not Connected yet" to indicate that no wallet is connected.

## How It Works:
When you click the "Connect Wallet" button, the webpage checks to see if the Pelagus Wallet extension is available in your web browser.
If the wallet is detected, the webpage asks for permission to access the account information from the wallet.
If permission is granted, the first account's address from the wallet is displayed on the webpage, showing that the connection was successful.
If the wallet is not found or there's an issue with the connection, the webpage either asks you to install the Pelagus Wallet or logs an error message for troubleshooting.

[![Connecting Pelagus](https://github.com/TsarenkoKir/Pelagus-Onboarding/assets/26483223/fb54427d-d56f-4795-8c6c-a3baddf8c8ea)](https://youtu.be/9rFBPJK19wQ)

To run http-server:

`npm install --global http-server`

`http-server`

**Here is a step-by-step video guide: https://youtu.be/9rFBPJK19wQ**


