# STL Physics Simulator

A browser-based rigid body physics simulator for STL files with real-time interaction capabilities. To my knowledge, this is the first free and open-source STL physics simulator that provides a complete graphical user interface, eliminating the need for command-line operations.

## Features

- **Real-Time Physics**: Powered by Ammo.js (a port of Bullet Physics)
- **Interactive Manipulation**: 
  - Drag objects in 3D space
  - Hold Shift while dragging to constrain rotation
  - Use mouse wheel to adjust height in constrained mode
  - Right-click to toggle object grounding
- **Advanced Visualization Options**:
  - Toggle collision mesh visibility
  - Display center of mass
  - Show ground projection markers
  - Adjustable wireframe and material properties
- **Physics Controls**:
  - Start/Stop simulation
  - Step-by-step simulation mode
  - Reset scene
  - Configurable physics parameters
- **Customizable Environment**:
  - Adjustable lighting conditions
  - Grid visibility options
  - Ground plane properties
  - Background color

## Getting Started

1. Download repository
2. Open file STL Physics Simulator.html located in STL Physics Simulator folder

## Usage

1. Click "Choose Files" and select your STL
2. Use the top toolbar for main controls:
   - Start/Stop physics simulation
   - Step through physics
   - Reset scene
   - Toggle visualization options
3. Use the right sidebar to adjust:
   - Physics parameters (gravity, damping, friction)
   - Visual properties (colors, opacity)
   - Environment settings (lighting, ground)

## Interaction Guide

- **Left Click + Drag on Obect**: Move objects
- **Right Click on Obect**: Toggle object grounding
- **Shift + Left Click + Drag**: Constrain rotation while moving
- **Mouse Wheel While Holding Object**: Adjust height in constrained drag mode
- **Right Click + Drag**: Orbit camera
- **Middle Click + Drag**: Pan camera
- **Mouse Wheel**: Zoom camera

## Technical Details

The simulator uses:
- Three.js for 3D rendering
- Ammo.js for physics calculations
- STL format for 3D models
- Custom collision mesh generation
- Optimized rigid body dynamics

## Browser Compatibility

Tested and working on:
- Chrome
- Firefox

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Please provide a good description of your changes as i am new to pull requests.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments

- Bullet Physics Engine
- Three.js Community
- Ammo.js Contributors
