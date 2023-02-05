# webpack-template

A template for my preferred webpack/ESLint/Prettier set up. New projects can clone this repo with some minor adjustments.

Need to install node_modules in your new project after cloning the repo. Run the following codes in your terminal:

1. npm init

2. npm install -D babel-loader @babel/core @babel/preset-env webpack webpack webpack-cli --save-dev --save lodash --save-dev style-loader css-loader --save-dev csv-loader xml-loader toml yamljs json5 --save-dev --save-dev html-webpack-plugin --save-dev html-loader

You will also need to do some minor editing to the following in the package.json file:

1.  "name": "webpack-demo", //Change to your preferred name

2.  "description": "A template for my preferred webpack set up. New projects can start here", //Change to your preferred description

3.  "repository": {
    "type": "git",
    "url": "git+https://github.com/Stalloyde/webpack-template.git" //Change 'webpack-template' to your project's repo url
    },
4.  "bugs": {
    "url": "https://github.com/Stalloyde/webpack-template/issues" //Change 'webpack-template' to your project's repo url
    },

5.  "homepage": "https://github.com/Stalloyde/webpack-template#readme" //Change 'webpack-template' to your project's repo url

To deploy to gh-pages, run:

1. npm run build
2. commit and push to main branch
3. git add dist && git commit -m "Initial dist subtree commit" //feel free to edit commit message
4. git subtree push --prefix dist origin gh-pages

then, make sure gh-pages setting uses gh-pages as its source.
