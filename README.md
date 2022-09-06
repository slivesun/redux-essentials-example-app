# Redux Essentials教程示例

这个项目包含了Redux文档(https://redux)中的“Redux Essentials”教程中的设置和代码。js.org/tutorials/essentials/part-1-overview-concepts)。'masten'分支有一个已经准备好初始项目配置的提交。您可以使用它来遵循本教程中的说明。

The `tutorial-steps` branch has the actual code commits from the tutorial. You can look at these to see how the official tutorial actually implements each piece of functionality along the way.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), using the [Redux](https://redux.js.org/) and [Redux Toolkit](https://redux-toolkit.js.org/) template.

> **Note**: If you are using Node 17, this project may not start correctly due to a known issue with Webpack and Node's OpenSSL changes, which causes an error message containing `ERR_OSSL_EVP_UNSUPPORTED`.  
> You can work around this by setting a `NODE_OPTIONS=--openssl-legacy-provider` environment variable before starting the dev server.
> Details: https://github.com/webpack/webpack/issues/14532#issuecomment-947012063

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
