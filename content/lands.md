---
title: Lands
description: How to claim, expand, manage roles, and merge claims with the Lands plugin on BoonCraft.
---
# Lands (BoonCraft)

> TL;DR: Use **claim blocks** or **/lands create** to start, **/claim** or **/claim auto** to expand, **/lands setspawn** to set a home (costs $500), and **/lands view** to see borders. BoonCraft has **no taxes/upkeep**; camps auto‑delete after 24 hours.

---

![](https://www.youtube.com/watch?v=DyApy3uRSFI)

---

## 1) Claiming your first land

### a) Claim blocks (the easiest way)

On first join you receive **claim blocks** (they look like grass blocks; hover text says _Claim Block_). You can **earn more** via **crates**, **playtime milestones**, or **buy** them in shops.

- **Place a claim block** to claim the chunk you’re standing in **for free**.

- If you **don’t** already own or belong to any land, placing a claim block will **create a new land automatically** (no command needed).

- If you **already** own a land or you’ve been **invited** to someone else’s, create your own land first:
```
/lands create <name>
```

…then continue claiming with more claim blocks or the commands below.


> 💡 Tip (Java Edition): Press **F3+G** to show vanilla **chunk borders** so you know exactly what you’re claiming.

### b) Commands to create & expand

Create a land explicitly (handy if you want to name it first):

```
/lands create <name>
```

Then expand using either the **Lands** commands **or** BoonCraft’s aliases:

```
/lands claim        # claim current chunk
/lands claim auto   # toggle auto-claim while you walk (run again to turn off)

# Aliases enabled on BoonCraft (shorter):
/claim
/claim auto
```

### c) The bell & barrel (HQ and storage)

When you place your first territory, BoonCraft spawns an **HQ barrel** with a **bell on top**:

- You **can’t break** these directly; the **barrel has extra storage** and represents your land’s storage.

- To **move/remove the bell**: **left‑click** the bell once → in the bottom‑right of the UI choose **Relocate/Move Bell**. This removes it from the world.

- To **place it again later**: open the land menu and use the bell button while standing **inside** that land:

```
/lands   # or /land
```

Click your land → bottom‑right **bell icon** → places the bell at your feet.

### d) Set a land spawn (costs $500)

Set your land’s TP point:

```
/lands setspawn
```

> **Cost:** $500 in‑game money each time you set/move it—pick the spot carefully. Players can use `/lands spawn <land_name>` (or GUI) to teleport to a land’s spawn.

### e) Rename, icon, and entry message (Misc Settings)

You can rename via command **or** the menu.

- **Command:**

```
/lands rename <new-name>
```

_(Renaming costs $500; better to name it correctly up‑front with `/lands create <name>`.)_

- **Menu path:**

```
/lands → click your land → Miscellaneous Settings
```

In **Misc Settings**:

- **Name tag** → set land **name**

- **Sign** → set the **entry message**

- **Icon** → **place any item from your inventory** onto this icon to use as the land icon

---

## 2) Expanding your claim

### a) Spend claim blocks or use commands

- **Claim blocks**: place more to extend your borders for free.

- **Commands**:

```
/lands claim
/lands claim auto   # run again to turn off

# Short aliases
/claim
/claim auto
```


### b) Unclaiming

Changed your mind? You can unclaim at any time (and be refunded any claim blocks you used):

```
/lands unclaim
/lands unclaim auto   # auto-unclaim as you walk; run again to turn off

# Short aliases
/unclaim
/unclaim auto
```

---

## 3) Land View (see your borders)

Show/hide particle borders for the **selected** land:

```
/lands view
```

Make sure **Particles** are enabled in your Video Settings. (Use **F3+G** alongside `/lands view` for pixel‑perfect chunk alignment.)

---

## 4) Creating new claims (separate bases & dimensions)

### a) New claims via claim blocks

Placing a **claim block away from your existing territory** creates a **new land automatically** under your name (or `<name>_#` if you’ve already used that name).

### b) Dimension gotcha (Overworld/Nether/End)

If you start in the **Overworld** and then place a claim block in the **End/Nether**, those chunks can attach to the **same land** across dimensions. If your base will be in another dimension, explicitly create it there first:

```
/lands create <name>
```

### c) Naming first, then claiming

Because renaming can incur a fee, it’s smart to **create with the correct name** and then expand:

```
/lands create <name>
/lands claim        # or place claim blocks
```

### d) Selecting the active land (GUI or command)

Many actions apply to your **selected** land (including claim/unclaim). Select via either:

- **GUI**: `/lands` → **Shift‑click** a land to set it as the active land.

- **Command**:

```
/lands edit <land-name>
```


### e) Merging lands

Accidentally made two lands you want combined?

1. **Select** the land you want to **merge into** (GUI shift‑click or `/lands edit <target>`).

2. Run:

```
/lands merge <other-land-name>
```

3. Confirm in the UI.

---

## 5) Switching claims & the management menu

Open the main GUI anytime:

```
/lands    # or /land
```

From there, pick a land to manage. For command‑line users, select a land first:

```
/lands edit <land-name>
```

> ⚠️ About **aliases** on BoonCraft: `/claim`, `/unclaim`, `/map`, and `/view` are aliased for convenience, but **/map** also opens the Dynmap link. If you want Lands‑only behavior, prefer the explicit commands like `/lands map`, `/lands view`, etc.

---

## 6) Trusting players

Quick trust (uses your selected land):

```
/lands trust <player>
```

Or via GUI:

```
/lands → click your land → Player Management → Members → Trust Player
```

Enter the player’s name in chat when prompted.

---

## 7) Defining permissions (roles & flags)

Lands uses **roles** (Owner, Trusted, Member, Visitor, etc.) and **flags** (what each role can do). Adjust per land in the GUI:

```
/lands → click your land → Roles → choose a role → toggle permissions
```

Start strict for **Untrusted**, loosen for **Member**, and reserve **Admin** for your inner circle.

---

## Handy reference (BoonCraft aliases included)

- **Open menu:** `/lands` (or `/land`)

- **Create land:** `/lands create <name>`

- **Select active land:** `/lands edit <name>` (or GUI shift‑click)

- **Claim:** `/lands claim` | `/lands claim auto` _(aliases: `/claim`, `/claim auto`)_

- **Unclaim:** `/lands unclaim` | `/lands unclaim auto` _(aliases: `/unclaim`, `/unclaim auto`)_

- **Borders:** `/lands view` _(use with F3+G)_

- **Spawn:** `/lands setspawn` _(costs $500);_ `/lands spawn <land_name>`

- **Rename:** `/lands rename <new-name>` _(may cost)_

- **Merge:** `/lands merge <other-land>`
