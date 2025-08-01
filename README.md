# Bloons Tower Defense MVP

A simple, retro-style tower defense game inspired by Bloons Tower Defense, built with HTML5, JavaScript, and p5.js.

## 🎮 How to Play

### Objective
Defend against waves of balloons by strategically placing monkey towers. Prevent balloons from reaching the end of the path!

### Controls
- **Click anywhere on the game grid** to place a monkey tower
- **Upgrade Range ($50)** - Increases tower attack range
- **Upgrade Pierce ($50)** - Allows projectiles to hit multiple balloons
- **Restart** - Start a new game

### Game Mechanics

#### Balloon Types (Tiers)
1. **Red** - Basic balloon (1 health)
2. **Blue** - Pops into 1 red balloon
3. **Green** - Pops into 1 blue balloon  
4. **Yellow** - Faster speed, pops into 1 green balloon
5. **Black** - Pops into 2 yellow balloons
6. **White** - Pops into 1 black balloon

#### Tower System
- **Monkey Tower** - Your only defense unit
- **Range** - How far the tower can attack
- **Pierce** - How many balloons a projectile can hit
- **Damage** - How much damage each shot deals

#### Economy
- Start with $650
- Earn $5 for each balloon popped
- Spend money on tower upgrades

#### Victory Conditions
- **Win**: Survive all 5 rounds
- **Lose**: Lose all 40 lives

## 🚀 Features

- ✅ 15x15 grid-based gameplay
- ✅ Exact path replication from reference image
- ✅ 6 balloon tiers with proper popping mechanics
- ✅ Tower placement and upgrades
- ✅ 5 rounds with increasing difficulty
- ✅ Real-time projectile system
- ✅ Retro pixel art style
- ✅ Responsive UI with game stats
- ✅ Win/lose conditions

## 🛠️ Technical Details

### Built With
- **HTML5** - Game structure
- **CSS3** - Styling and layout
- **JavaScript** - Game logic
- **p5.js** - Graphics and animation

### Game Architecture
- **Grid-based system** for precise tower placement
- **Path-following balloons** with smooth movement
- **Projectile physics** with targeting system
- **Wave management** with spawn timing
- **Upgrade system** affecting all towers

## 📁 File Structure
```
ballonger/
├── index.html          # Main game file
└── README.md          # This file
```

## 🌐 Deployment

### Local Development
1. Clone this repository
2. Open `index.html` in your web browser
3. Start playing!

### GitHub Pages
1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" → "main"
4. Your game will be available at `https://username.github.io/ballonger/`

## 🎯 Game Strategy Tips

1. **Early Game**: Place towers near the path start to catch balloons early
2. **Mid Game**: Focus on range upgrades to cover more area
3. **Late Game**: Prioritize pierce upgrades for higher-tier balloons
4. **Positioning**: Place towers at path corners for maximum coverage
5. **Economy**: Balance between new towers and upgrades

## 🔧 Customization

The game is easily customizable by modifying the constants in the JavaScript:

- `GRID_SIZE` - Change grid cell size
- `COLS/ROWS` - Modify grid dimensions
- `BALLOON_COLORS` - Customize balloon appearances
- `PATH` - Create new path layouts
- `towerConfig` - Adjust tower properties

## 📝 License

This project is open source and available under the MIT License.

---

**Enjoy playing Bloons Tower Defense MVP!** 🎈🐒