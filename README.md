# React Three Fiber Car Model Demo

This is a demo project showcasing a 3D car model using React Three Fiber, a powerful library for creating 3D graphics in the browser with React. The car model is fully interactive, and includes animations for opening the doors, turning on the headlights, and starting the engine.

![Screenshot of the car model demo](https://raw.githubusercontent.com/adityakumar48/carshow/master/Screenshot%202023-04-02%20133614.png)

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:
```git clone https://github.com/your-username/react-three-fiber-car-model.git ```
2. Install the dependencies:
```npm install```
3. Start the development server:
```npm start```
4. Open your browser and navigate to `http://localhost:3000`.

## How it Works

The car model is created using [Blender](https://www.blender.org/), a popular open-source 3D modeling and animation tool. The model is exported as a `.glb` file, which is then loaded into the React Three Fiber scene using the `useGLTF` hook.

The animations are created using [react-spring](https://www.react-spring.io/), a popular animation library for React. Each animation is defined as a separate `useSpring` hook, which is then passed to the car model components as props.

## Contributing

If you'd like to contribute to this project, feel free to submit a pull request or open an issue. Make sure to follow the [code of conduct](CODE_OF_CONDUCT.md) and the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- [React Three Fiber](https://github.com/pmndrs/react-three-fiber)

## Contact

If you have any questions or comments about this project, feel free to contact me at your-email@example.com.
