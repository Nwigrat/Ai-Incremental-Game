# AI Tycoon Web 🧠

A JavaScript incremental game where you build and grow an AI company from a single developer to a global computing empire. Experience the journey from garage startup to potential technological singularity through both gameplay and story.

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
  - Cluster Palaces with specialized chips
  - Quantum Cores and processing
  - Hivemind Arrays for collective intelligence
  - Automated Fabrication Systems
  - Synapse Farms with neuromorphic hardware
  - Orbital Compute Armadas
  - AI Governors for policy
  - Terraform Networks
  - Singularity Hubs
  - Meta Cloud Infrastructure

### Key Systems
- Bulk buy modes (1x, 10x, max)
- Click animations with value display
- Achievement system with sound effects
- Rich story system with milestone-triggered lore
- Late-game content management
- Persistent saves (local storage)
- Import/export save data
- Configurable number formatting
- Auto-save with adjustable interval

### Story & Lore
Experience your company's growth through narrative:
- From garage startup to global phenomenon
- Story cards unlock at key milestones
- Watch your decisions shape the future of AI
- Multiple story arcs and technological eras:
  - The Garage Days
  - Gaming Hardware Era
  - Research Breakthroughs
  - Datacenter Expansion
  - Foundation Model Revolution
  - Planetary Scale Operations
  - Quantum Computing Era
  - Hivemind Emergence
  - Approaching Singularity

### UI Features
- Clean, responsive interface
- Quick-access generator panel
- Detailed stats tracking
- Progress indicators
- Collapsible late-game content
- Achievement notifications with sound
- Story cards with smooth animations
- Revenue Per Second (RPS) tracking
- Upgrade multiplier display
- IPO progress tracking with percentage
- Focused status messages

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
- Single file application (~1200 lines)
- Uses modern browser features:
  - Local Storage for saves
  - Web Audio API for sounds
  - RequestAnimationFrame for game loop
  - CSS Grid/Flexbox for layout
  - CSS Animations for effects
  - CSS Transitions for UI
  - Modern JavaScript features:
    - Optional chaining
    - Nullish coalescing
    - Template literals
    - structuredClone for state

## Development

The entire game is contained in `index.html`. Key sections:

```javascript
// Game configuration
const Generators = { ... }  // Production units from interns to quantum cores
const Upgrades = { ... }    // Multiplier upgrades and power-ups
const Achievements = { ... } // Unlock conditions and story triggers
const Lore = { ... }        // Story beats and narrative content

// Core systems
const State = { ... }            // Game state and progression
function loop(ts) { ... }        // Main game loop with passive income
function refresh() { ... }       // UI updates and notifications
function showLoreCard() { ... }  // Story card display system
```

## Save System

- Auto-saves to localStorage
- Configurable save interval (5-600 seconds)
- Import/export saves as JSON
- Backwards compatible with new content
- Graceful handling of new features
- Safe state migration for updates

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