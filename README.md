> @schibstedspain/theme-basic is deprecated. Please use @schibstedspain/sui-theme instead.

# SUI Components Basic Theme

This repository contains:

* Generic variables to initialize default values and component styles
* A set of placeholders ready to style your component (buttons, tabs, forms, grid system...)
* Functions and mixins helpers

## Usage

Import `theme-basic` into your sui-component including the path in `index.scss`:

```
@import '../node_modules/@schibstedspain/theme-basic/src/index';
```

If you want to customize your components, create your own theme and add it to yor component just __before__ the theme-basic import.

```
@import '../custom-settings';
@import '~@schibstedspain/theme-basic/src/index';
```


## Update
If you need to update any of these variables please pull request.
