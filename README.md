# SUI Components Theme

This repository contains:

* Generic variables to initialize default values and component styles.
* A set of placeholders ready to style your component (buttons, tabs, forms, grid system...).
* Functions and mixins helpers.

## Usage

Import `sui-theme` into your sui-component including the path in `index.scss`:

```
@import '../node_modules/@schibstedspain/sui-theme/src/index';
```

If you want to customize your components, create your own theme and add it to your component just __before__ the sui-theme import.

```
@import '../custom-settings';
@import '~@schibstedspain/sui-theme/src/index';
```


## Update
If you need to update any of these variables please pull request.
