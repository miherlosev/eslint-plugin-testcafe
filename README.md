# eslint-plugin-testcafe

ESLint rules for [testcafe](https://github.com/DevExpress/testcafe)

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-testcafe`:

```
$ npm install eslint-plugin-testcafe --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-testcafe` globally.

## Recommended configuration

This plugin export a recommended configuration that enforce good practices.

To enable this configuration use the extends property in your .eslintrc config file:
```
{
  "plugins": [
    "testcafe"
  ],
  "extends": "plugin:testcafe/recommended"
}
```

See [ESLint documentation](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) for more information about extending configuration files.