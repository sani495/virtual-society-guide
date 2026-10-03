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

-# Every new member adds 🪙 500 to your treasury automatically.

---

## 4. Set Up Your Job Market

Pick which jobs your server offers:
`/create-job slot:1 name:Miner minpay:50 maxpay:150 level:1`
Repeat for slots 1 through 5. Set different pay ranges for different jobs.

Set work cooldown: `/set-cooldown minutes:60`
Set XP per level: `/set-levels xp:10 pay:5`
---

## 5. Set Up Your Shop (Optional)

Turn on role shop: /shop-toggle type:roles state:on`
Add a role: `/setshoprole slot:1 role:@VIP price:5000`

Same for channels: 
`/shop-toggle` type:channels state:on`
`/setshopchannel slot:1 channel:#vip-lounge price:10000`
---

## 6. Configure Welcome Messages (Optional)
`/admin-config:welcomechannel value:1234567890123456789
`/admin-config:welcomemsg value:Welcome, {user}! Glad you're here.`

# If welcome system is on, every member who joins automatically funds your server 🪙500. 
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
| `/config` | Welcome + server name |
| `/setup` | Bot-owner only: global settings |
| `/setjob` | Configure job slots |
| `/setshoprole` | Add role to shop |
| `/setshopchannel` | Add channel to shop |
| `/shopsettings` | Turn shops on/off |
| `/removeshopitem` | Remove item from shop |
| `/serverbank` | View treasury |
| `/serverloan` | Borrow from global bank |
| `/loanpay` | Repay a loan |
| `/gov-grant` | Governors only: grant money |
| `/redeem` | Redeem a promo code |

---

## Need Help?

Join **TwiceDice Support**. The government lives there.