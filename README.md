# Pizza Joint

## Project Structure

## Dependencies

- `react`: ^18.2.0
- `react-dom`: ^18.2.0
- `react-router-dom`: ^6.11.2
- `framer-motion`: ^10.12.16
- `react-scripts`: 5.0.1
- `@testing-library/jest-dom`: ^5.16.5
- `@testing-library/react`: ^13.4.0
- `@testing-library/user-event`: ^13.5.0
- `web-vitals`: ^2.1.4

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`

Launches the test runner in the interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder.

### `npm run eject`

Ejects the app, giving you full control over the configuration files.

## Components

### App

The main component that sets up the routes and manages the state of the pizza order. It is implemented in [`App.js`](src/App.js).

### Header

The header component that displays the logo and title. It is implemented in [`Header.js`](src/components/Header.js).

### Home

The home component that welcomes the user and provides a button to start creating a pizza. It is implemented in [`Home.js`](src/components/Home.js).

### Base

The component that allows the user to choose a pizza base. It is implemented in [`Base.js`](src/components/Base.js).

### Toppings

The component that allows the user to choose pizza toppings. It is implemented in [`Toppings.js`](src/components/Toppings.js).

### Order

The component that displays the user's pizza order and shows a modal after a delay. It is implemented in [`Order.js`](src/components/Order.js).

### Modal

The modal component that asks the user if they want to make another pizza. It is implemented in [`Modal.js`](src/components/Modal.js).

### Loader

The loader component that displays an animated loader. It is implemented in [`Loader.js`](src/components/Loader.js).

## Styles

The styles for the project are defined in [`App.css`](src/App.css) and [`index.css`](src/index.css).

## Fonts

The project uses the "Quicksand" font, which is included in the project as [`Quicksand-Light.woff`](src/Quicksand-Light.woff) and [`Quicksand-Light.woff2`](src/Quicksand-Light.woff2).

## Entry Point

The entry point for the project is [`index.js`](src/index.js), which sets up the React application and renders the `App` component inside a `BrowserRouter`.

To install and run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/joseernestoroldan/pizza-joint.git
    ```

2. Navigate to the project directory:
    ```sh
    cd pizza-joint
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

4. Start the development server:
    ```sh
    npm start
    ```

5. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.