# STL Physics Simulator

A browser-based rigid body physics simulator for STL files with real-time interaction capabilities. To my knowledge, this is the first free and open-source STL physics simulator that provides a complete graphical user interface, eliminating the need for command-line operations.

Right now there are some limitations, such as If you try to import mechanisms, the program will have a hard time with simulating them because the obect will start to glitch through each other. I am trying to fix this but since not many people have done this open source and not an huge servers, there is no where i can find answers to my problems. It still works alittle but im not happy with it right now. Please contribute if you feel you can make the program better. My code that makes a bunch of librarys work together isnt very long, so it wont take muuch time for a good programmer to contribute.

I am releasing it, faults and all, because there doesnt seem to be any Physic Simulators out there that are no code, open source, local, accept stl files, or have a GUI. Sure there are ones out there that have one or 2 of those, but not all of them.

Also even if you cant code, it would be great if someone could revamp the readme as its not as descriptive, clear and consise al i would like.

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

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0).
This means:

✅ You can share, copy, and redistribute the code
✅ You can adapt, modify, and build upon the code
❌ You cannot use the code for commercial purposes
❌ You cannot distribute your modifications under a different license
📝 You must give appropriate credit and indicate if changes were made
📝 You must distribute your modifications under the same license

## Acknowledgments

- Bullet Physics Engine
- Three.js Community
- Ammo.js Contributors
