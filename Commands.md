# 📖 Command List

Every command in Virtual Society, sorted by category.

All commands use the **`/`** prefix.

---

## 💰 Money & Banking

| Command | What it does |
|---|---|
| `/balance` | View your wallet, bank, and net worth |
| `/balance user:@someone` | View another player's balance |
| `/deposit amount:500` | Move cash into your bank |
| `/withdraw amount:500` | Move money from your bank to cash |
| `/pay user:@someone amount:500` | Send cash to another player |

Type `all` instead of a number to move everything:
`/deposit amount:all`

---

## 💼 Jobs

| Command | What it does |
|---|---|
| `/jobs` | See available jobs on this server |
| `/apply slot:1` | Apply for a job |
| `/work` | Work a shift and earn money |
| `/jobinfo` | See your job, level, and XP |
| `/quitjob` | Leave your current job |

---

## 👤 Profile

| Command | What it does |
|---|---|
| `/profile` | View your profile |
| `/profile user:@someone` | View another player's profile |
| `/setbio` | Set your profile bio |

You can also set your bio from `/settings` → User → Bio.

---

## 🛒 Shop

| Command | What it does |
|---|---|
| `/shop` | Browse roles and channels for sale |
| `/buy-item type:roles slot:1` | Buy a role |
| `/buy-item type:channels slot:1` | Buy channel access |
| `/sell-item type:roles slot:1` | Sell a role back for a refund |
| `/sell-item type:channels slot:1` | Sell channel access back |

---

## 🏦 Banks & Loans

| Command | What it does |
|---|---|
| `/serverbank` | View this server's treasury |
| `/globalbank` | View the world treasury |
| `/serverloan amount:10000` | Borrow from the global bank (admins) |
| `/loanpay amount:10000` | Repay your server's loan (admins) |

---

## 🏛️ Government

| Command | What it does |
|---|---|
| `/government` | View the government and partnered servers |
| `/partner server_id:...` | Partner a server (governors) |
| `/unpartner server_id:...` | Remove a partner (governors) |
| `/gov-grant amount:5000` | Grant money to a server (governors) |
| `/setgovserver` | Set this server as the government (owner) |

---

## 🎟️ Promo Codes

| Command | What it does |
|---|---|
| `/redeem code:CODE_NAME` | Redeem a promo code into your server's treasury |
| `/promo-create code:... value:... uses:...` | Create a promo code (governors) |
| `/promo-list` | List active promo codes (governors) |
| `/promo-delete code:...` | Delete a promo code (governors) |

---

## ⚙️ Settings & Config

| Command | What it does |
|---|---|
| `/settings` | Open the settings hub |
| `/config` | Welcome channel and message (admins) |
| `/set-server-name` | Name your server in the network (admins) |
| `/fund amount:50000` | Add money to your treasury (admins) |

---

## 🔧 Job Configuration

| Command | What it does |
|---|---|
| `/setjob slot:1 name:Miner minpay:50 maxpay:150 level:1` | Create a job (admins) |
| `/removejob slot:1` | Delete a job (admins) |
| `/setcooldown minutes:60` | Set work cooldown (admins) |
| `/setlevels xp:10 pay:5` | Set XP scaling (admins) |
| `/setcoin emoji:🪙` | Set currency emoji (admins) |

---

## 🛠️ Shop Configuration

| Command | What it does |
|---|---|
| `/shopsettings type:roles state:on` | Turn the role shop on or off (admins) |
| `/shopsettings type:channels state:on` | Turn the channel shop on or off (admins) |
| `/setshopitem type:roles slot:1 target:ROLE_ID price:5000` | Add a role to the shop (admins) |
| `/setshopitem type:channels slot:1 target:CHANNEL_ID price:10000` | Add a channel to the shop (admins) |
| `/removeshopitem type:roles slot:1` | Remove a shop item (admins) |

---

## 🔒 Bot Owner Commands

These are only available to the bot developer.

| Command | What it does |
|---|---|
| `/setup` | Manage governors, funds, resets |
| `/construction` | Lock or unlock systems during development |

---

## 🆘 Getting Help

- **Stuck on a command?** Check the [FAQ](FAQ)
- **Something broke?** Report it in **TwiceDice Support**
- **New to the bot?** Start with [Getting Started](Getting-Started)

---

*Last updated: 10/12/26*