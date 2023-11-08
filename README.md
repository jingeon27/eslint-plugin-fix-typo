# eslint-plugin-fix-typo

This is a plugin that corrects typos.

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-fix-typo`:

```sh
npm install eslint-plugin-fix-typo --save-dev
```

## Usage

Add `fix-typo` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "fix-typo"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "fix-typo/rule-name": 2
    }
}
```

## Rules

<!-- begin auto-generated rules list -->
TODO: Run eslint-doc-generator to generate the rules list.
<!-- end auto-generated rules list -->


