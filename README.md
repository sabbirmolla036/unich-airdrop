# 🚀 Unich Tool

**Unich Tool** is an automation utility that supports fast and efficient account registration, idling (farming), and task automation for airdrop platforms.

---

## 🔥 Features

- ✅ Auto account registration  
- 🔄 Auto token & refresh token management  
- 🌱 Auto mining (farming)  
- 📋 Auto task execution  
- 🌍 Proxy support with validation  
- 🧠 Captcha solving via CapMonster  

---

## 🛠 Installation & Setup

### 🔗 Download & Install

1. Go to the [GitHub Repository](https://github.com/your-repo/unich-airdrop)
2. Click **Code > Download ZIP**
3. Extract the ZIP file
4. Open the extracted folder

---

## ⚙️ Configuration

Edit the `config.json` file based on your use case.

### 💼 Farming / Task Running Mode

```json
{
  "numberThread": 25,
  "autoMining": true,
  "checkProxy": true,
  "autoTasks": true,
  "autoReg": false,
  "getToken": false,
  "checkToken": false,
  "refCode": "HRTBV9",
  "CAPMONSTER_API_KEY": "your_api_key"
}
## 🆕 Account Registration Mode
json
Copy
Edit
{
  "numberThread": 10,
  "autoMining": false,
  "autoTasks": false,
  "autoReg": true,
  "getToken": false,
  "checkToken": false,
  "refCode": "HRTBV9",
  "CAPMONSTER_API_KEY": "your_api_key"
}
Replace "your_api_key" with your actual CapMonster API key.

## 📂 Required Files
hotmail.txt
pgsql
Copy
Edit
email|password|refresh_token|client_id
➡ One email per line. Do not remove lines during task execution.

proxy.txt
makefile
Copy
Edit
ip:port:username:password
➡ One proxy per line.

account.txt
pgsql
Copy
Edit
email|password
➡ One account per line after registration.

## ❌ Do NOT modify:
token.txt

refreshToken.txt

tasks_status.json

These are auto-generated and managed by the tool.

## 🖥 Running the Tool
### ✅ On Windows
Make sure config.json, hotmail.txt, account.txt, proxy.txt are set up.

Run the tool by opening unich.exe.

### ✅ On Linux
bash
Copy
Edit
chmod +x unich
./unich
## 🔑 Token Handling
Tokens are auto-saved to token.txt and refreshToken.txt.

If the token expires, copy the refresh token into token.txt.

If both token and refresh token expire:

Set "getToken": true in config.json.

Delete token.txt and refreshToken.txt.

Run the tool to generate new tokens.

## 📘 License
© 2025 Tunzankies. All rights reserved.

# 🌐 Useful Links
🔗 Airdrop Dashboard

🔗 CapMonster

### 🙏 Thanks & Good Luck!
Automate smarter. Earn faster. 🚀

yaml
Copy
Edit

---

You can copy and paste this directly into your `README.md` file in the GitHub repository root. Let me know if you want a downloadable `.md` file or additional formatting like badges or images.



