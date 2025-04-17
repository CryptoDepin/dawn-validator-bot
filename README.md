# 🎉 Dawn validator bot is Ready! 🎉
We’ve released two versions of software for farming Dawn:

1) 🔥 FREE version works only with accounts registered through it.
  * **Download free version in our Telegram bot:** 

2) 💎 PAID version supports any accounts — register using your own referral code!
  * **DM us for the paid version in Telegram:** 

- 📩 Telegram chat: 
- 📩 Telegram channel: 
- 📩 Developer: 

- - -

**🚀 What can our software do?**

* ✅ Account registration
* ✅ Email verification
* ✅ Farming
* ✅ Collecting rewards
* ✅ Collect statistics from accounts

**💪 Why is DAWN better than alternatives?**

* 1️⃣ Traffic efficiency — consumes much less data compared to competitors.
* 2️⃣ Speed — works significantly faster than other solutions.
* 3️⃣ Smart proxy manager — instantly switches proxies if a connection drops.
* 4️⃣ Optimized performance — no need for 3–5–10 servers. You only need 1–2 servers for full functionality. For Windows, the optimal thread count is 15K, with some servers capable of handling even more!

**🛠 What else can we offer?**

* Unlimited residential proxies (price negotiable, depends on server count).
* Traffic-based proxies — just $1.5 per GB 
* Another our softwares:
   * [Grass](https://github.com/CryptoDepin/grass-bot)
   * [Dawn](https://github.com/CryptoDepin/dawn-validator-bot)
   * [LayerEdge](https://github.com/CryptoDepin/layeredge-bot)
   * [Gradient](https://github.com/CryptoDepin/gradient-network-bot)
   * [NodeGo](https://github.com/CryptoDepin/nodego-bot)
   * [Bless](https://github.com/CryptoDepin/bless-network-bot)
   * [DeSpeed](https://github.com/CryptoDepin/despeed-bot)
   * [NodePay](https://github.com/CryptoDepin/nodepay-bot)
   * [Monadscore](https://github.com/CryptoDepin/monadscore-bot)

Invite your friends and colleagues to join! 🚀

# How to use? Documentation
### Installation
**Software will autimatically install in: C:\Program Files (x86)\Dawn_free_v1.2**

**You cannot change the location directory of the software**

### Setting Up CAPTCHA Key
* In the `Data` folder, open the `config.ini` file.
* Specify the CAPTCHA-solving service `api key` for 2captcha.com

### Adding Email Accounts
* In the `Data` folder, use the `emails.txt` file.
* Add email accounts in the format: `email:password`.
* Ensure the email accounts support `IMAP`; otherwise, verification will fail.

### Setting IMAPS
* In the `Data` folder, open the `imaps.txt` file.
* Add the IMAP of the emails you use in this format: `email domain|imap`. For example: `desedumail.com|imap.firstmail.ltd`, where `desedumail.com` is an email domain, and `imap.firstmail.ltd` - its IMAP.

### Adding Proxies
* In the `Data` folder, use the `proxy.txt` file.
* Add proxies in the format: `ip:port` or `login:password@ip:port`.

### Account Registration
* Successful registrations will be saved in the `reg_goods.txt` file.
* Emails that failed to register will be listed in the `reg_bads.txt` file.

### Email Verification
* Place accounts to be verified in the `accs.txt` file in the `Data` folder.
* Use the `proxy.txt` file for proxies in the specified format.
* Successfully verified accounts will be saved in `approveEmail_goods.txt`.
* Failed verifications will be logged in `approveEmail_bads.txt`. These accounts can be reattempted, as some might pass on subsequent tries.

### Account authorization
* Place accounts to be authorized in the `accs.txt` file in the `Data` folder.
* Use the `proxy.txt` file for proxies in the specified format.
* Successfully authorized accounts will be saved in `auth_goods.txt`.
* Failed authorization will be listed in `auth_bads.txt`. These accounts can be reattempted, as some might pass on subsequent tries.

### Preparing Accounts for Farming
**YOU HAVE TO COMPLETE FULL PROCESS BEFORE FARMING: Register account, approve email, authorize to account after approve. Without all this actions accounts not ready for farming**
* Move successfully registered accounts from `auth_goods.txt` to the `accs.txt` file in the `Data` folder.
* Ensure `proxy.txt` contains proxies in the required format.
* Start the farming process.

### Collecting Rewards
* The **Collect Rewards** module gathers available rewards for linking telegram, discord, twitter (but you don't need to have real accounts).
* Add accounts for reward collection to the `accs.txt` file in the `Data` folder.
* Use `proxy.txt` for proxies.

### Collecting statistics
* The **Collect statistics** module gathers available amount of points from every account and save it to file `statistics_goods.txt`
* Add accounts for statistics collection to the `accs.txt` file in the `Data` folder.
* Use `proxy.txt` for proxies.

# 🔗 Contacts
* 📩 Telegram chat: 
* 📩 Telegram channel: 
* 📩 Developer: 
