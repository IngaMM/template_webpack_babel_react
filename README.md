Webpack-Babel-React-Configuration according to https://www.valentinog.com/blog/babel/ (with a simplified react part)

1. Run npm install
2. In development: Run npm run start. http://localhost:8080 opens in a browser.
3. For production: Run npm run build. Production-ready files (index.html & main.js) are created in the dist-folder.

Attention:

- This folder includes a file .babelrc which might easily be forgotten when copying it.
- Before committing a project to github, create a gitignore file that excludes the folder node_modules
