# Webpack, TypeScript, Eslint

1. Create a folder.
2. Use `cd ./folderName` to enter in folder.
3. Install npm:
   - run `npm install`;
   - run `npm init`
4. Install Webpack:
   - run `npm i -D webpack webpack-cli webpack-dev-server`;
   - create `webpack.config.js`;
   - create `./src/index.ts` file
5. Install TypeScript:
   - run `npm i -D typescript ts-loader`;
   - run `tsc --init`;
6. Setting Webpack:
   - run `npm i -D html-webpack-plugin mini-css-extract-plugin css-loader sass-loader copy-webpack-plugin`
   - put favicon.ico in `./public/`
   - create `./src/assets/` folder
7. Install Eslint
   - run `npm i -D eslint-webpack-plugin eslint`
   - run `npm i -D eslint-plugin-import eslint-config-airbnb-typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin`
8. Add scripts in package.json 
```javascript
  "scripts": {
    "build": "webpack",
    "dev": "webpack serve --env develop",
    "lint": "eslint src"
  },
```
