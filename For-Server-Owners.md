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
`/set-server-name name:Your Server Name`

This is how you show up in the government's partner list.

---

## 3. Fund Your Treasury

Before anyone can work, your treasury needs money: `/fund amount:100000`

🗒️ Your server is currently at level 1. You'll only be able to fund `100,000` at a time until you level up.

**Server Levels coming soon!**

Any admin with **Manage Server** permission can fund the treasury. 100k
lasts a while for a small server.

**Every new member adds 🪙 500 to your treasury automatically.**

> Heads-up: funding prints new money into the global economy. Don't
> overdo it — it inflates everyone's wallets over time.
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

Turn on role shop: `/shop-toggle type:roles state:on`

Add a role: `/create-shop type:roles slot:1 target:(ID OF TYPE) price:1000`

Same for channels: 

`/shop-toggle type:channels state:on`

`/create-shop type:channel slot:1 target:(ID OF TYPE) price:1000`

> **⚠️ Before adding channels to the shop:**
>
> The bot needs **Manage Roles** at the server level, AND its role must
> be **above** the role that owns the channel you're selling.
>
> If you skip this, buyers will see a "Channel Setup Issue" error and
> won't be charged. See [FAQ](https://github.com/sani495/virtual-society-guide/blob/main/FAQ.md) for the full fix.

---

## 6. Configure Welcome Messages (Optional)
`/welcome-config action:welcomechannel value:123456789123456789`

`/welcome-config action:welcomemsg value:Welcome, {user}! Glad you're here.`

If welcome system is on, every member who joins automatically funds your server 🪙500. 
`{user}` will be replaced with the new member's mention.

---

## 7. Read Your Treasury
`/bank`
Shows:
- Server and Global treasuries
- Debt owed to global bank
- Loans taken

---

## Admin Commands Cheat Sheet

| Command | Purpose |
|---|---|
| `/admin-config` | Welcome + server name |
| `/owner-config` | Bot-owner only: global settings |
| `/fund` | Fund money to your own treasury.
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