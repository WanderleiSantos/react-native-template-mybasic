# React Native Template Basic

This project is to simplify the creation of React Native projects, a pre-configured basic model, avoiding delays in the development environment configuration process.



## Done with

- React Native;
- React Navigation;
- React Native Gesture Handler;
- Async Storage;
- Axios;
- Prop-Types;
- Styled-Components;
- Reactotron;
  - reactotron-react-native;
- EditorConfig;
- Prettier;
- Babel;
  - babel-eslint;
  - babel-plugin-root-import;
- Eslint;
  - eslint-config-airbnb;
  - eslint-plugin-import;
  - eslint-plugin-jsx-a11y;
  - eslint-plugin-react;
  - eslint-plugin-react-native;
  - eslint-import-resolver-babel-plugin-root-import;

## Running

    react-native init AwesomeExample --template mybasic

## Instructions

- Delete the `App.js` file that is in the root of the project.(The `"App.js"` that you will use is located in the `src` folder with the name `index.js`);
- Go to the: `android > app > src > main > java > com > your_project_name > MainActivity.java`
- Access: https://reactnavigation.org/docs/en/getting-started.html

## Structure

```
mybasic
├── src/
│   ├── config/
│   │   └── ReactotronConfig.js
│   ├── pages/
│   │   └── Main/
│   │       └── index.js
│   ├── services/
│   │   └── api.js
│   ├── index.js
│   └── routes.js
├── babel.config
├── dependencies.json
├── devDependecies.json
├── index.js
├── jsconfig.json
├── package.json
├── .editorconfig
├── .eslintrc.json
├── .gitattributes
├── .gitignore
├── .prettierrc
```


