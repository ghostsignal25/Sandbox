# Physics Simulation - Ball Box

An interactive physics simulation game featuring plastic balls bouncing inside a metal container with realistic physics and sound effects.

## Features

### 🎱 Ball Physics
- **Multiple ball types** with different sizes and densities
- **Color-coded by density**:
  - 🔴 Red: Low density (0.001)
  - 🔵 Teal: Medium density (0.003)
  - 🔵 Blue: High density (0.005)
  - 🟡 Yellow: Very high density (0.008)
- Realistic gravity simulation
- Collision physics with friction and restitution

### 📦 Metal Container
- Semi-transparent walls so you can see the balls inside
- Walls prevent balls from escaping
- Realistic metal collision properties

### 🎮 Interactive Controls
- **Gravity Slider**: Adjust gravity strength from 0x to 2x
- **Flip Box Button**: Reverses gravity direction (flips the box upside down)
- **Shake Box Button**: Applies random forces to simulate shaking
- **Reset Button**: Resets all balls to initial positions and gravity to default
- **Drag & Drop**: Click and drag balls to move them around (they stay inside the box)

### 🔊 Sound Effects
- **Collision sounds** generated in real-time using Web Audio API
- **Metal sounds**: Higher frequency for ball-wall collisions
- **Plastic sounds**: Lower frequency for ball-ball collisions
- Volume based on collision velocity

## How to Use

1. Open `physics-simulation.html` in a web browser
2. Watch the balls fall and bounce due to gravity
3. Use the controls to interact with the simulation:
   - Adjust the gravity slider to change gravitational force
   - Click "Flip Box" to flip the container upside down
   - Click "Shake Box" to shake all the balls
   - Drag balls with your mouse to reposition them
   - Click "Reset" to start over

## Technical Details

### Technologies Used
- **HTML5 Canvas**: For rendering
- **Matter.js**: 2D physics engine
- **Web Audio API**: Real-time sound generation
- **Vanilla JavaScript**: Game logic and interactivity

### Physics Properties
- **Gravity**: Default 1.0 (adjustable 0-2x)
- **Ball restitution**: 0.8 (bounciness)
- **Ball friction**: 0.3
- **Wall restitution**: 0.6
- **Wall friction**: 0.3

### Ball Specifications
| Type | Radius | Density | Color |
|------|--------|---------|-------|
| Low Density | 30px | 0.001 | Red (#ff6b6b) |
| Medium Density | 25px | 0.003 | Teal (#4ecdc4) |
| High Density | 35px | 0.005 | Blue (#45b7d1) |
| Very High Density | 20px | 0.008 | Yellow (#f9ca24) |

## File Structure
```
physics-simulation.html    # Main simulation file (standalone)
PHYSICS_SIMULATION_README.md    # This documentation file
```

## Browser Compatibility
- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Requires JavaScript enabled
- Requires Web Audio API support

## Tips
- Heavier (denser) balls fall faster and hit harder
- Try setting gravity to 0 for a zero-gravity experience
- Use the shake feature after flipping for chaotic fun
- Drag balls to the top and release for maximum bounce
- Listen to the different sounds when balls hit walls vs each other

## License
Open source - feel free to modify and enhance!
