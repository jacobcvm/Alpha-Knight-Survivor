# 🛡️ Knight Survivor - Pre-Alpha

Welcome to the **Knight Survivor** pre-alpha!  
This is a top-down survival game featuring melee and ranged combat, leveling up and fighting increasing waves of enemies.

---

## 🎮 Current Features

### 🔹 Movement
- Screen Settings: Borderless windowed mode 1920-1080 resolution
- **W, A, S, D** or **Arrow Keys** to move the player
- mouse movement (left,right) makes the character flip_horizontally
- ** Hold the **Left Mouse Button** to move the camera (resets on release)

### 🔹 Combat
- **Melee Weapon**: 
   - Orbiting rocks around the player
   - Sword
- **Ranged Weapon**: Rock projectile follows the mouse position
   - The player becomes black when hit
   - Coming soon

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
  - Become black when hit
  - Sword attacks pushes them away from the player 
  - Move back and forth and attack when they have a collision with the player
  - Spawn outside the screen and move toward the player
  - Spawn more frequently as time passes
  - Stronger enemies spawn less often than the weaker ones
  - Drop XP on death

### 🔹 Magnet Mechanic
- XP will follow the player when within range until it is collected

---

## 🧪 User Interface (UI)

During gameplay, the UI displays:
- **Hp bar: HP / Max HP**
- **Xp bar: Level: XP / Max XP**
- **Kills**
- **Elapsed Time**
- **Score**

---

## 🗂️ Menus

### Main Menu
- Start Game
- View Highscore
- Quit Game

### Highscore
- Delete Highscore
- Return to main menu

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
- More damage  

**Rock Projectile and Sword Attack**
- Faster attack speed  
- More damage  

##### Character Upgrades
- Increased health regeneration  
- Increased max HP  
- Increased movement speed  
- Increased XP pickup range

---

## 🎁 Droppable Items
- **Movement speed boost-> duration: 10s
- **Attack boost-> duration: 20s
- **Health Potion**: restore 50% of health 
- **Magnet**:
- Increases pickup range and movement speed for:
- (XP drops, attack boost and movement speed): duration: 10 s

---

## 🚧 Features To-Do

### ⚙️ Gameplay
- [ ] Add level design with obstacles  
- [ ] Add invisible walls to limit map size
- [ ] Limit maximum number of enemies and drops 
- [ ] Show active boosts in the UI 
- [ ] Add rarity system for upgrades
- [ ] screen effect when player gets hit
- [ ] ennemy stat scaling (increases over time)

### ⚔️ Weapons
- [ ] Add second ranged weapon   

### 📋 UI & Menus
- [ ] Add options in the main menu  
- [ ] Add credits in the main menu 

### 🧩 Assets
- [ ] Find and integrate more free assets  

---

## 💡 Notes

This is an **early pre-alpha** version of the game. Many features are subject to change as development progresses.

---

