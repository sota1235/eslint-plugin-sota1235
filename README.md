# eslint-plugin-sota1235

[![Build Status](https://travis-ci.org/sota1235/eslint-config-sota1235.svg?branch=master)](https://travis-ci.org/sota1235/eslint-config-sota1235)

My own rules for [ESLint](http://eslint.org/).

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-sota1235`:

```
$ npm install eslint-plugin-sota1235 --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-sota1235` globally.

## Usage

Add `sota1235` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "sota1235"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "sota1235/rule-name": "error"
    }
}
```

## Supported Rules

* `no-document-cookie`: Find 'document.cookie' from the code.
