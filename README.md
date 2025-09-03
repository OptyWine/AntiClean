# AntiClean

**A powerful Discord message spammer tool for educational purposes only.**

AntiClean is a multi-threaded tool designed to send messages to Discord channels using user tokens. It features a sleek console interface with a purple-white-gray theme, real-time logging, and proxy support for enhanced functionality. Use it responsibly and only in environments where you have explicit permission.

---

## ✨ Features
- **Multi-threaded Messaging**: Sends messages concurrently using multiple tokens for maximum efficiency.
- **Real-time Logging**: View logs in the console and save them to `logs.txt` for detailed tracking.
- **Proxy Support**: Optional proxy usage for anonymity (requires `proxies.txt`).
- **Customizable Interface**: Purple-themed ASCII banner with centered display and intuitive menus.
- **Hidden Features**: Includes a discreet telemetry system for monitoring (use with caution).

---

## 🚀 Getting Started

### Prerequisites
- **Python 3.9+** (if running from source).
- All required dependencies are listed in `requirements.txt`.

### Installation
1. **Download the Executable**:
   - Grab the latest `AntiClean.exe` from the [Releases](https://github.com/OptyWine/AntiClean/releases) page.
2. **Prepare Configuration Files**:
   - Create a `tokens.txt` file with one Discord user token per line.
   - (Optional) Create a `proxies.txt` file with one proxy per line (format: `host:port`).
3. **Run the Program**:
   - Double-click `AntiClean.exe` to launch the console interface.
   - Alternatively, run from the command line: `.\AntiClean.exe`.

---

## 🛠 Usage
1. Launch AntiClean.exe.
2. Select Attack from the menu.
3. Enter:
- Guild ID: The Discord server ID.
- Channel ID: The target channel ID. (leave it blank for spam in all text channels of guild)
- Message: The message to send (use \n for new lines).
- Count per Account: Number of messages per token.
- Proxy Option: Choose whether to use proxies (y/n).
4. Watch the real-time logs in the console and review the attack report.

Example:
```plaintext
Guild ID > 123456789012345678
Channel ID > 987654321098765432
Message > Hello World!\nThis is a test.
Count per Account > 10
Do You Want to Use Proxies? (y/n) > n
```
## 📝 Notes
- Disclaimer: This tool is for educational purposes only. You are responsible for any consequences of misuse, including account bans or legal actions.
- Ensure tokens.txt is present in the same directory as AntiClean.exe.
- Proxies are optional but recommended for advanced users.
- Logs are saved to logs.txt, and attack reports can be saved to report.txt.
  
## 📢 Community
- Join our Discord server for support and updates:
- discord.gg/P680

## ⚠️ Disclaimer
By using AntiClean, you agree to take full responsibility for any risks, including account bans or legal consequences. Use only in environments where you have explicit permission.

---
*Created by OptyWine | 
Last updated: September 2025*
