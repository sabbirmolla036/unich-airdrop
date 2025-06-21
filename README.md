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
