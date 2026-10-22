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
| `/job-list` | See available jobs on this server |
| `/apply slot:1` | Apply for a job |
| `/work` | Work a shift and earn money |
| `/job-info` | See your job, level, and XP |
| `/quit-job` | Leave your current job |

---

## 👤 Profile

| Command | What it does |
|---|---|
| `/profile` | View your profile |
| `/profile user:@someone` | View another player's profile |
| `/set-profile` | Set your profile bio |

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

## 🏆 Leaderboards

| Command | What it does |
|---|---|
| `/leaderboard` | See the top 3 servers and top 3 users |

---

## 🏦 Banks & Loans

| Command | What it does |
|---|---|
| `/bank` | View the entire treasury! |
| `/server-loan amount:10000` | Borrow from the global bank (admins) |
| `/loan-pay amount:10000` | Repay your server's loan (admins) |
| `/credits` | View or spend your server's Credits |
| `/donate target:server amount:500` | Donate cash to the server treasury or global bank |

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
| `/welcome-config` | Welcome channel and message (admins) |
| `/set-server-name` | Name your server in the network (admins) |
| `/fund amount:50000` | Add money to your treasury (admins) |

---

## 🔧 Job Configuration

| Command | What it does |
|---|---|
| `/create-job slot:1 name:Miner minpay:50 maxpay:150 level:1` | Create a job (admins) |
| `/remove-job slot:1` | Delete a job (admins) |
| `/set-cooldown minutes:60` | Set work cooldown (admins) |
| `/set-coin emoji:🪙` | Set currency emoji (admins) |
| `/set-levels` | Set XP scaling, or force a user to a specific level |
| `/add` / `/take` | Add or remove cash from a user (uses server treasury) |
---

## 🛠️ Shop Configuration

| Command | What it does |
|---|---|
| `/shop-toggle type:roles state:on` | Turn the role shop on or off (admins) |
| `/shop-toggle type:channels state:on` | Turn the channel shop on or off (admins) |
| `/create-shop-item type:roles slot:1 target:ROLE_ID price:5000` | Add a role to the shop (admins) |
| `/create-shop-item type:channels slot:1 target:CHANNEL_ID price:10000` | Add a channel to the shop (admins) |
| `/remove-shop-item type:roles slot:1` | Remove a shop item (admins) |

---

## 🔒 Bot Owner Commands

These are only available to the bot developer. (Except for /government)

| Command | What it does |
|---|---|
| `/owner-config` | Manage governors, funds, resets |
| `/lockdown` | Lock or unlock systems during development |
| `/government` | View the government and partnered servers |
| `/gov-grant amount:5000` | Grant money to a server (governors) |
| `/set-government` | Set this server as the government (owner) |


---

## 🆘 Getting Help

- **Stuck on a command?** Check the [FAQ](https://github.com/sani495/virtual-society-guide/blob/main/FAQ.md)
- **Something broke?** Report it in **[TwiceDice Support](https://discord.gg/Fwavq3GNxs)**
- **New to the bot?** Start with [Getting Started](https://github.com/sani495/virtual-society-guide/blob/main/Getting-Started.md)

---

*Last updated: 10/22/26*