# 🛡️ Knight Survivor - Pre-Alpha

Welcome to the **Knight Survivor** pre-alpha!  
This is a top-down survival game featuring melee and ranged combat, leveling up, and increasing waves of enemies.

---

## 🎮 Current Features

### 🔹 Movement
- **W, A, S, D** or **Arrow Keys** to move the player
- **Left Mouse Button** to move the camera (resets on release)

### 🔹 Combat
- **Melee Weapon**: Orbiting rocks around the player
- **Ranged Weapon**: Rock projectile follows the mouse position

### 🔹 Enemies
1. **Thief**
2. **Anomaly**
3. **Dead**
   - Moves fast
4. **Flying Demon**
   - Very tanky  
   - Fires ranged fireball attacks  
   - Drops a chest that grants a level-up

#### Enemy Behavior
- All enemies:
  - Play a hit animation and stop moving when hit
  - Spawn outside the screen and move toward the player
  - Spawn more frequently as time passes
  - Stronger enemies spawn less often
  - Drop XP on death

### 🔹 Magnet Mechanic
- XP will follow the player when within range until it is collected

---

## 🧪 User Interface (UI)

During gameplay, the UI displays:
- **HP / Max HP**
- **XP / Max XP**
- **Kills**
- **Elapsed Time**

---

## 🗂️ Menus

### Main Menu
- Start Game
- View Highscore
- Quit Game

### Pause Menu (via `ESC`)
- Resume Game
- Return to Main Menu

---

## 🔼 Leveling System

### Level Up Mechanics
- When **current XP ≥ max XP**, the player levels up
- Choose **1 of 3 random upgrades**

#### 📈 Passive Bonus (each level up)
- `+20` Max HP  
- `+5` Damage

#### 🔧 Upgrades

##### Weapon Upgrades

**Rotating Rocks (Melee)**
- Faster rotation  
- Bigger rocks  
- Larger orbit radius  
- Additional rock  

**Projectile (Ranged)**
- Faster attack speed  
- More damage  

##### Character Upgrades
- Increased health regeneration  
- Increased max HP  
- Increased movement speed  
- Increased XP pickup range

---

## 🎁 Droppable Items

- **Health Potion**: +50 HP  
- **Magnet**: Temporarily increases XP pickup range and XP movement speed (10 seconds)

---

## 🚧 Features To-Do

### ⚙️ Gameplay
- [ ] Add upgrade limits  
- [ ] Limit maximum number of enemies and drops  
- [ ] Add rarity system for upgrades  
- [ ] Implement a proper XP and HP bar  
- [ ] Add level design with obstacles  
- [ ] Add invisible walls to limit map size  
- [ ] Stop walk animation when idle  

### ⚔️ Weapons
- [ ] Add second ranged weapon  
- [ ] Add second melee weapon  

### 📋 UI & Menus
- [ ] Add options in the main menu  
- [ ] Add credits button  

### 🧩 Assets
- [ ] Find and integrate more free assets  

---

## 💡 Notes

This is an **early pre-alpha** version of the game. Many features are subject to change as development progresses.

---

