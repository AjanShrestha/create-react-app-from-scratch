# Create React App From Scratch

> Build something from scratch. Understand the tools. [Link](https://blog.cloudboost.io/create-a-react-application-from-scratch-part-1-introduction-b2e66dfb3aae)

## Step 1 :: [Initialization and the First File](https://medium.com/@TeeFouad/create-a-react-application-from-scratch-part-2-initialization-and-the-first-file-c7e0ecdaa6bf)

- Project documentaiton is very important. Make sure package.json file contains descriptive and useful information.
- Use an editor config file so that developers working on same project will adhere the same coding styles across different editors and IDEs.
- Instead of installing packages globally use npx to execute local package binaries.

## Step 2 :: [Using ES2015+ Syntax](https://medium.com/@TeeFouad/create-a-react-application-from-scratch-part-3-using-es2015-syntax-4ab0ba7a4254)

- Use Babel to convert ES2015+ syntax to normal JavaScript to ensure cross-browser compatibility

## Step 3 :: [Enforcing a Style Guide](https://medium.com/@TeeFouad/create-a-react-application-from-scratch-part-4-enforcing-a-style-guide-afebd2036938)

- ESLint for code linting
- AirBnb's Style Guide or other
- Linting non-standard ES2015+ Syntax -- babel-eslint
- Adding an npm script for linting
- Enforce linting before making a commit -- husky

## Step 4 :: [Setting up and Express Server](https://medium.com/@TeeFouad/create-a-react-application-from-scratch-part-5-setting-up-an-express-server-7abd8e89420e)

- The server file
- Creating the app.js file
- Creating routes and handling requests
- Setting up the view engine
- Handling server errors
- Handling 404 errors
- Creating a public directory
- Reading environment variables
- Logger, BodyParser and CookieParser
