# common-eslint

Common eslint rules accros all projects. Based on AirBnb standards.


## Usage

Include it in your `package.json` -

```js
"common-eslint": "CQSCloud/common-eslint.git"
```

Adapt your project-root `.eslintrc` to contain -

```js
{
  "extends": "common-eslint",
  "parser": "babel-eslint"
}
```
