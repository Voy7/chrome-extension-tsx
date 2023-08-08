# chrome-extension-tsx
A template for creating chrome extensions with TypeScript, React, Sass, and Webpack.

---

## Getting Started
Install the required packages by running `npm install` or `npm i`.

- `npm run start` or `npm start` will start the Webpack watch script, allowing for live reloading of the Popup and Content Scripts code. This can be considered the development mode.
- `npm run build` will create the clean distribution version of the extension in the `dist` directory.

**Note:** Both the live-reloading and distribution code will be located in the `dist` directory, depending on which script was run last. (This folder is in `.gitignore`, so you will not have one until you run one of the scripts)