# eslint-config-airbnb-babel
> Babel support for Airbnb's ESLint config

This config extends the AirBNB rules to work with [eslint-plugin-babel](https://github.com/babel/eslint-plugin-babel).

## Install

```sh
npm install eslint-config-airbnb-babel --save-dev
```

## Configure
This configuration must be placed after which ever version of the AirBnB rules you are using in your `.eslintrc` file:

```json
{
  "extends": ["airbnb", "airbnb-babel"]
}
```

----
&copy; David J. Bradshaw 2020
License: MIT
