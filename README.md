## Eslint, Prettier, Husky, Lint-staged configurations for React project

#### Please, make sure you are using node.js version >= 10 
##
#### Firstly, you need to install a few packages to your dev-dependencies:

**Using npm:**

    npm i eslint husky lint-staged prettier eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react --save-dev
**Using yarn:**

    yarn add -D eslint husky lint-staged prettier eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react


#### Secondly, you need to add `lint` command to `scripts` block in your `package.json`:
    "scripts": {
        // your commands
        "lint": "eslint 'src/**/*.js' --quiet --fix"
      }

#### Then you can copy files (.eslintrc, .huskyrc, .lintstagedrc, .prettierrc) from the repository to your project for using the tools

##
### If you have any questions feel free to [contact me](mailto:bodyaperhalyuk@gmail.com)
