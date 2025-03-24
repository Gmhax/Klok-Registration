# Klok Registration Tool

![Klok](https://klokapp.ai/favicon.ico)  

A powerful automation tool to register multiple accounts on [Klok](https://klokapp.ai?referral_code=GVJRESB4) using Ethereum wallets and proxies.

## 🚀 Features
- Bulk registration of Ethereum wallets
- Proxy support for anonymity
- Referral code integration for better rewards
- Multi-threaded execution for speed
- Automatic logging of success and failure attempts

## 📥 Installation
### Prerequisites
Ensure you have the following installed:
- **Node.js** (v16 or higher)
- **Git**

### Clone the repository
```sh
git clone https://github.com/Gmhax/Klok-Registration
cd Klok-Registration
```

### Install dependencies
```sh
npm install
```

## ⚙️ Configuration

### Edit `config.js`
Update your referral code and adjust the number of threads for parallel processing.
```js
const REFERRAL_CODE = {
  referral_code: "YOUR_REFERRAL_CODE", // Change this to your own referral code
};
const THREADS = 10; // Adjust based on system capability
```

### Add Private Keys
Store private Ethereum wallet keys inside `priv.txt`. Each key should be on a new line.
```txt
privateKey_1
privateKey_2
```

### Configure Proxies
Store proxies inside `proxies.txt` in the following format:
```txt
http://user:pass@ip:port
http://user:pass@ip:port
```

## ▶️ Running the Tool
### On macOS/Linux
```sh
node main.js
```

### On Windows
```sh
node main.js
```

## 📜 Logging
- **success.txt**: Stores successfully registered wallet addresses.
- **fail.txt**: Stores failed registration attempts.

## 📞 Support
For any issues, open an issue on the [GitHub repository](https://github.com/rpchubs/Klok-Registration/issues) or reach out to the Klok community.

---
Happy registering! 🎉

