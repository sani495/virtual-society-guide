# 🔧 For Server Owners

Adding Virtual Society to your server. Takes 5 minutes.

---

## 1. Invite the Bot

Use the invite link the bot owner shared. Standard permissions:
- Send Messages
- Embed Links
- Manage Roles (for role shop)
- Manage Channels (for channel shop)

---

## 2. Set Up Your Server
`/admim-config action:setservername value:Your Server Name`

This is how you show up in the government's partner list.

---

## 3. Fund Your Treasury

Before anyone can work, your treasury needs money:

`/setup action:serverfund value:100000`

You (or a governor) can fund it. 100k lasts a while for a small server.

Every new member adds 🪙 500 to your treasury automatically.

---



You (or a governor) can fund it. 100k lasts a while for a small server.

**Every new member adds 🪙 500 to your treasury automatically.**

---

## 4. Set Up Your Job Market

Pick which jobs your server offers:
`/create-job slot:1 name:Miner minpay:50 maxpay:150 level:1`

Repeat for slots 1 through 5. Set different pay ranges for different jobs.

Set work cooldown: `/set-cooldown minutes:60`

Set XP per level: `/set-levels xp:10 pay:5`


---

## 5. Set Up Your Shop (Optional)

Turn on role shop: `/shop-settings type:roles state:on`

Add a role: `/create-shop type:roles slot:1 target:(ID OF TYPE) price:1000`

Same for channels: 

`/shopsettings type:channels state:on`

`/create-shop type:channel slot:1 target:(ID OF TYPE) price:1000`

---

## 6. Configure Welcome Messages (Optional)
`/admin-config:welcomechannel value:1234567890123456789

`/admin-config:welcomemsg value:Welcome, {user}! Glad you're here.`

If welcome system is on, every member who joins automatically funds your server 🪙500. 
`{user}` will be replaced with the new member's mention.

---

## 7. Read Your Treasury
`/server-bank`
Shows:
- Balance
- Debt owed to global bank
- Loans taken

---

## Admin Commands Cheat Sheet

| Command | Purpose |
|---|---|
| `/admin-config` | Welcome + server name |
| `/owner-config` | Bot-owner only: global settings |
| `/create-job` | Configure job slots |
| `/create-shop`| Make a shop for both role and channel |
| `/shop-toggle` | Turn shops on/off |
| `/remove-shop-item` | Remove item from shop |
| `/server-bank` | View treasury |
| `/server-loan` | Borrow from global bank |
| `/loan-pay` | Repay a loan |
| `/gov-grant` | Governors only: grant money |
| `/redeem` | Redeem a promo code |

---

## Need Help?

Join **TwiceDice Support**. The government lives there.