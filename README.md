# React Starter Lite

This is a _minimal_ starter kit I use for **rapid prototyping** and small hobby projects. It relies on modern browser features and is not suitable for widespread production use.

## Usage

```sh
git clone https://github.com/hughfm/react-starter-lite.git
cd react-starter-lite
npm install
npm run develop
```

## What do you get?

In essence, this is just an HTML file with [React](https://reactjs.org/) included as a script tag.

When you write your JavaScript in `src/`, it will be processed by [Babel](https://babeljs.io/) and output into `build/`, where it will be served from.

All Babel does here is transpile [JSX](https://reactjs.org/docs/introducing-jsx.html) into plain Javascript. There's **no** transpiling to earlier ES versions, and **no** module bundling, so your browser needs to support ES6 and modules.

My base config for [ESLint](https://eslint.org/) and deployment on [Now](https://zeit.co/) are thrown in for good measure.
