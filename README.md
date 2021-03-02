# CircleCI React Starter

This package is the Continuous Integration full configure. It is starter template using Raact library (Create React App).

How to configure Continuous Delivery using Netlify?

Netlify:
```shell
1. Go to settings > build & deploy and scroll down to build hooks.
2. Click in Add build Hook
3. Write a descriptive name to your build and save it.
4. Copy the url that was generated on save. Paste it somewhere because we'll need it later.
```

Configure an environment variable in CircleCI:
```shell
1. Go to your CircleCI app.
2. Click in Jobs.
3. Click in the settings icon next to your project's name.
4. We entered the settings of that specific Job. Click where it says Environment Variables.
5. Click in Add Variable
6. We'll give it a descriptive name like awesome_endpoint and in the value paste that endpoint url I told you to save previously.
7. Click in Add Variable again.
```
Almost done ;)

## 🚀 Quick Start

1.  **Install dependencies**

    ```shell
    npm install
    ```

2.  **Runs the app in the development mode.**
    
    ```shell
    npm start
    ```
    Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## 📦 What's inside?
* React
* Prettier and ESLint
* CircleCI
* Netlify CLI
* Husky and Lintstaged

---

```shell
npm test
```

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

```shell
npm run build
```

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

```shell
npm run eject
```

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

```shell
npm run netlify:deploy
```
