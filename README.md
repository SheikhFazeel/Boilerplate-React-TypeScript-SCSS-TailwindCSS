# Create React + TypeScript + SCSS + TailwindCSS App
React, typescript, scss, tailwind css Starter
Boilerplate for Tailwind CSS Configured without ejecting from [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will hot reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## React

[React](https://github.com/facebook/react) is a JavaScript library for building user interfaces.

Due to its awesome renderer system, there are many [React Renderor](https://github.com/chentsulin/awesome-react-renderer). So React can be not used only Web, for example, used by [React Native](https://reactnative.dev/).

Let's dive into React and Vite can use with React.

## TypeScript

[TypeScript](https://github.com/microsoft/TypeScript) is a superset of JavaScript. It is just one of NPM library, but it provides an original compiler.

When you use TypeScript with React, you can write JSX with TypeScript, called TSX. Then you can develop views written by  **Type-Safe** template.

## Tailwind CSS

[Tailwind CSS](https://tailwindcss.com/) is modern utility-first CSS framework. It provides many CSS rules, but these are purged when production builds. So developers do not worry about CSS asset size for performance optimization.

In VSCode, I recommend to use [intellisense extension](https://tailwindcss.com/docs/intellisense).

Frequently, React developers are worried about how to write CSS in TSX(JSX) template. You must choose from CSS Modules, [styled-components](https://styled-components.com/), [linaria](https://github.com/callstack/linaria), and so on.
Additionally, CSS architecture is difficult about scoping, e.g. BEM, FLOCSS.

When you decide to use Tailwind, you only write utility-first CSS classes, you don't have to worry about them!
