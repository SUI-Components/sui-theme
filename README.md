# SUI Components Theme

This repository contains:

* Generic variables to initialize default values and component styles.
* A set of placeholders ready to style your component (buttons, tabs, forms, grid system...).
* Functions and mixins helpers.

## Usage

Import `sui-theme` into your sui-component including the path in `index.scss`:

```
@import '../node_modules/@schibstedspain/sui-theme/lib/index';
```

If you want to customize your components, create your own theme and add it to your component just __before__ the sui-theme import.

```
@import '../custom-settings';
@import '~@schibstedspain/sui-theme/lib/index';
```

## Upgrade from theme-basic@7
Compatibility variables are still available to import manually.

**Import only what you need, in inheritance order**

For instance:
```
@import '../custom-settings';
@import '~@schibstedspain/sui-theme/lib/settings-compat-v7/color';
@import '~@schibstedspain/sui-theme/lib/settings-compat-v7/spacing';
@import '~@schibstedspain/sui-theme/lib/index';
```

Find below de compat varible groups available:

* [settings-compat-v7/color](https://github.com/SUI-Components/sui-theme/blob/master/src/settings-compat-v7/_color.scss)
* [settings-compat-v7/font](https://github.com/SUI-Components/sui-theme/blob/master/src/settings-compat-v7/_font.scss)
* [settings-compat-v7/spacing](https://github.com/SUI-Components/sui-theme/blob/master/src/settings-compat-v7/_spacing.scss)
* [settings-compat-v7/box-style](https://github.com/SUI-Components/sui-theme/blob/master/src/settings-compat-v7/_box-style.scss)
* [settings-compat-v7/animation](https://github.com/SUI-Components/sui-theme/blob/master/src/settings-compat-v7/_animation.scss)
* [settings-compat-v7/layout](https://github.com/SUI-Components/sui-theme/blob/master/src/settings-compat-v7/_layout.scss)
* [settings-compat-v7/components](https://github.com/SUI-Components/sui-theme/blob/master/src/settings-compat-v7/_components.scss)


**Also, if you need it all for older components, you can do**
```
@import '~@schibstedspain/sui-theme/lib/settings-compat-v7/index';
@import '~@schibstedspain/sui-theme/lib/index';
```

## Update
If you need to update any of these variables please pull request.
