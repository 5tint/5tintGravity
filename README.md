# [Feb 19th 2026] NOTE: This project is end-of-life. I stopped working on it in April 2025. I thought I would pick it up again but I'm not really interested. Therefore, sometime in the not too far future I will probably release one more update to make it somewhat stable and finished (v1.0) and then stop development entirely. \5

# 5tintGravity - 2D Planet Simulator

A physics-based 2D planetary simulator built with Python and Pygame. The simulator allows users to create and observe planetary motion under gravitational forces, including dynamic collisions and configurable settings.

## Features
- **Realistic Gravity Simulation**: Planets attract each other based on Newtonian physics.
- **Collisions**: Planets collide and bounce off each other with kinetic energy conservation.
- **Customizable Settings**: Adjust parameters such as gravity, time step, and background color.
- **Dynamic Planet Creation**: Planets can be defined in a `build.txt` file with fixed or highly customizable random properties.
- **Flant**: Own custom scripting language for `build.txt` - check 0.2.0 release notes for documentation
- **Keybinds for Interaction**:
  - `SPACE`: Pause/Resume simulation.
  - `I`: Send all planets toward the center.
  - `O`: Send all planets away from the center.
  - `R/G/B`: Increase red, green, or blue color in the background.
  - `W`: Increase all background colors.
  - `0`: Reset background to black.
