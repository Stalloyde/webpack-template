# webpack-template
A template for my preferred webpack set up. New projects can start here

Need to install node_modules in your new project. Run the following codes in your terminal:

npm init -y
npm install webpack webpack-cli --save-dev --save lodash --save-dev style-loader css-loader --save-dev csv-loader xml-loader toml yamljs json5 --save-dev --save-dev html-webpack-plugin


To deploy to gh-pages, run:

git add dist && git commit -m "Initial dist subtree commit" //feel free to edit commit message
git subtree push --prefix dist origin gh-pages

then, make sure gh-pages setting uses gh-pages as its source.