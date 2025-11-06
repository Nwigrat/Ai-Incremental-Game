# AI Tycoon Web 🧠

A JavaScript incremental game where you build and grow an AI company from a single developer to a global computing empire.

## Features

### Core Gameplay
- 🚀 Click to "Ship Features" and earn funding
- 💰 Purchase generators to earn passive income
- 🔄 Progress through multiple tiers of AI technology
- 📈 Go public (IPO) to earn reputation multipliers
- 💡 Buy upgrades to boost your production

### Generator Progression
- Early Game: Start with intern developers and GPU rigs
- Mid Game: Scale to datacenters and foundation models
- Late Game: Unlock advanced technologies like:
  - Quantum Cores
  - Hivemind Arrays
  - Orbital Compute Armadas
  - Planetary-Scale Networks
  - And more!

### Key Systems
- Bulk buy modes (1x, 10x, max)
- Click animations with value display
- Achievement system with sound effects
- Persistent saves (local storage)
- Import/export save data
- Configurable number formatting
- Auto-save with adjustable interval

### UI Features
- Clean, responsive interface
- Quick-access generator panel
- Detailed stats tracking
- Progress indicators
- Collapsible late-game content
- Achievement notifications
- IPO progress tracking

## Getting Started

1. Open `index.html` in a modern web browser
2. Click the 🚀 to start earning funding
3. Purchase generators to earn passive income
4. Unlock upgrades to multiply your earnings
5. Achieve milestones to earn achievements
6. Go public when ready to reset with bonuses

## Technical Details

- Pure vanilla JavaScript, HTML, and CSS
- No external dependencies
- Single file application (~1000 lines)
- Uses modern browser features:
  - Local Storage for saves
  - Web Audio API for sounds
  - RequestAnimationFrame for game loop
  - CSS Grid/Flexbox for layout
  - CSS Animations for effects

## Development

The entire game is contained in `index.html`. Key sections:

```javascript
// Game configuration
const Generators = { ... }  // Production units
const Upgrades = { ... }    // Multiplier upgrades
const Achievements = { ... } // Unlock conditions

// Core systems
const State = { ... }       // Game state
function loop(ts) { ... }   // Main game loop
function refresh() { ... }  // UI updates
```

## Save System

- Auto-saves to localStorage
- Configurable save interval (5-600 seconds)
- Import/export saves as JSON
- Backwards compatible with new content

## Browser Support

Requires a modern browser with support for:
- ES6+ JavaScript
- CSS Grid/Flexbox
- Web Audio API
- Local Storage
- RequestAnimationFrame

## License

MIT License - Feel free to use, modify, and distribute!

## Credits

Created as a learning project exploring incremental game mechanics and vanilla JavaScript game development.