# React JS Webpack Template

This is a basic React setup project template with Webpack for bundling and development server.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate into the project directory:

   ```bash
   cd react-js-webpack-template
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Available Scripts

In the project directory, you can run the following scripts:

### `npm start`

Runs the app in development mode.\
Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `dist` folder.\
It bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

## Project Structure

```
react-js-webpack-template/
  ├── node_modules/         # Dependencies installed by npm
  ├── public/               # Public assets
  │   └── index.html        # HTML template
  ├── src/                  # Source files
  │   ├── App.js            # Main React component
  │   └── index.js          # Entry point for React application
  ├── .babelrc              # Babel configuration
  ├── package.json          # Project configuration and dependencies
  ├── webpack.config.js     # Webpack configuration
  └── README.md             # Project documentation
```

## Dependencies

### Development Dependencies

- [@babel/core](https://www.npmjs.com/package/@babel/core)
- [@babel/preset-env](https://www.npmjs.com/package/@babel/preset-env)
- [@babel/preset-react](https://www.npmjs.com/package/@babel/preset-react)
- [babel-loader](https://www.npmjs.com/package/babel-loader)
- [html-webpack-plugin](https://www.npmjs.com/package/html-webpack-plugin)
- [webpack](https://www.npmjs.com/package/webpack)
- [webpack-cli](https://www.npmjs.com/package/webpack-cli)
- [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server)

### Dependencies

- [react](https://www.npmjs.com/package/react)
- [react-dom](https://www.npmjs.com/package/react-dom)

## Author

- Jan Kosiński

## License

This project is licensed under the ISC License.
