## Fluid Simulation WebGL Application

This is a WebGL-based fluid simulation application that utilizes GPU acceleration for real-time fluid dynamics. The simulation allows users to interact with the fluid using mouse or touch input, creating colorful and dynamic visualizations.

### Features

- **Fluid Simulation:** The application employs a stable fluid simulation algorithm with adjustable parameters such as resolution, dissipation, and curl to control the behavior of the fluid.

- **Interactive Input:** Users can interact with the simulation by clicking and dragging the mouse or using touch input. The simulation responds to input by adding colorful splats to the fluid.

- **Configuration Options:** Various configuration options are available, allowing users to customize the simulation's behavior, including resolution, dissipation rates, pressure iterations, and more.

- **Image Textures:** The simulation supports the use of image textures as input, enhancing the visual richness of the fluid. Two image textures (`mediaOne` and `mediaTwoe`) are included as examples.

- **Bloom and Sunrays Effects:** Users can enable bloom and sunrays effects to enhance the overall visual appeal of the simulation.

### Usage

1. Open the `index.html` file in a WebGL-compatible web browser.

2. Interact with the simulation using the mouse or touch input. Experiment with different configuration options to observe changes in the fluid dynamics.

### Configuration

The `config` object at the beginning of the script allows you to fine-tune various parameters of the simulation. Adjust these values to achieve different visual effects and behaviors.

### Compatibility

The application checks for WebGL 2.0 support and falls back to WebGL 1.0 if necessary. Additionally, it checks for the availability of certain extensions to optimize performance.

### Mobile Optimization

The simulation includes optimizations for mobile devices, adjusting parameters for a smoother experience on smaller screens.

### Credits

This application is based on a WebGL fluid simulation framework and has been extended and customized for this specific implementation.

### License

This project is licensed under the [MIT License](LICENSE).

### Acknowledgments


- Special thanks to Transient Labs for coding the fluid simulation algorithm.

### Notes

- For the best experience, use a modern web browser with WebGL support.

- Performance may vary depending on the hardware and browser used.

Feel free to explore, experiment, and integrate this fluid simulation into your projects!
