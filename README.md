# Double Pendulum Simulator

A physics-based simulation demonstrating chaotic motion through an interactive double pendulum system. This web application provides a visual representation of the complex dynamics that emerge from a seemingly simple mechanical system.

## Features

- Real-time physics simulation of a double pendulum system
- Interactive controls for adjusting:
  - Lengths of both pendulum arms
  - Masses of both bobs
  - Initial angles
  - Gravity strength
  - Damping coefficient
- Visual trail effect showing the path of motion
- Pause/Resume functionality
- Smooth animations and clean UI

## Physics

The simulator implements the full equations of motion for a double pendulum system, accounting for:

- Gravitational forces
- Centripetal forces
- Angular momentum
- Energy conservation
- Damping effects

The chaotic nature of the double pendulum becomes apparent when running the simulation - even slight changes in the initial conditions can lead to dramatically different trajectories over time.

## Usage

- **Adjust the sliders and input fields to set up your desired configuration:**
  - **Length 1 & 2**: Adjust the length of each pendulum arm (0.5m - 2.5m)
  - **Mass 1 & 2**: Set the mass of each bob
  - **Angle 1 & 2**: Set the initial angles (-180° to 180°)
  - **Gravity**: Modify the gravitational acceleration
  - **Damping**: Control energy dissipation

- **Click "Start" to begin the simulation**
- **Use the Pause/Resume button to control the animation**
- **Observe how different parameters affect the pendulum's behavior**

## Technical Details

Built using vanilla JavaScript and HTML5 Canvas, the simulator employs:

- Numerical integration for solving differential equations
- Optimized rendering with trail effects
- Responsive canvas sizing
- Event-driven architecture for UI controls

The simulation maintains physical accuracy while providing smooth visual feedback and real-time interaction.
