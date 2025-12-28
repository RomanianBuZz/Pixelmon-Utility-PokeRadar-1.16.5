# Pixelmon Helper Mod (Minecraft)

Hello! This is my first Minecraft mod. I like coding, but I’m still at the beginning of the journey and I still have a lot to learn.

This mod is designed for playing on **Pixelmon servers** and includes a few quality-of-life features.

---

## Features

### 1) Integrated Pokémon Detector
The mod includes a Pokémon detector with a **search bar**.

- **Open/Search key:** `Delete`
- **Examples:**
  - Single Pokémon: `ditto`
  - Multiple Pokémon (use commas): `ditto, torchic, kakuna,`
- **Filters:**
  - By size and gender:
    - Example: `torchic(size:small,huge)(gen:m)`
    - This will only search for a Torchic that is **small or huge** and **male**.

**Automatic detections (no search needed):**
- Detects **all Legendary Pokémon**
- Detects Boss Pokémon of tier: **Epic / Legendary / Ultimate**
- They only need to **spawn near you**.

**Detection colors:**
- Normal Pokémon: **white line**
- Legendary Pokémon: **red line**
- Boss Pokémon: **blue line**

---

### 2) HUD + Autobot (Farming Mode)
- **Open HUD:** `Ctrl + Insert`
- In the HUD you can:
  - Enable/disable **Legendary detection**
  - Enable/disable **Boss detection**
  - Configure the autobot homes

#### Starting the autobot
- **Start key:** `Insert`
- Also, you start the autobot using the **Insert** key.

#### What does the autobot do?
The autobot is made for farming a specific Pokémon by moving between two spawn locations.

Example (Ditto farm):
1. Go to a Ditto spawn area and set a home:
   - `/sethome ditto`
2. Go to another Ditto spawn area and set a second home:
   - `/sethome ditto2`
3. In the HUD, set:
   - **home ditto**
   - **home ditto2**
4. The bot will move between these two locations until it detects the target Pokémon.

**When the target is detected:**
- A sound will notify you
- The sound will not stop until you **enter a battle** with that Pokémon

---

### 3) Inventory Auto-Sort
The mod includes an **auto-sort button** for your inventory:
- Press the button and all items in your inventory will be sorted automatically.

---

## Updates
I will keep this mod updated and post future improvements and new features here.

If you want to support this project:
- PayPal: paypal.me/freshbuzz1996

Thanks for checking it out!
