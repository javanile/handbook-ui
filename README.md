# [Handbook UI](https://github.com/javanile/handbook-ui)
Handbook UI is a **starter CSS framework** that actually looks good.

[![npm](https://img.shields.io/npm/v/handbook-ui.svg)](https://www.npmjs.com/package/handbook-ui)
[![npm](https://img.shields.io/npm/l/handbook-ui.svg)](https://www.npmjs.com/package/handbook-ui)

## Getting Started
> Handbook UI is currently in **BETA**.  Try it out today and help us fine tune the look and feel!

**STEP 1: Install Using NPM**
```bash
npm install handbook-ui --save-dev
```
**STEP 2: Create SCSS file with your customizations**
```scss
/** 
 * file: style.scss
 * desc: my custom theme 
 */

@import 'node_modules/handbook-ui/src/scss/handbook-ui'

$brand-color: $color-yellow-100;
@import 'node_modules/handbook-ui/src/scss/handbook-ui-elements'

$nav-bg-color: $color-light-blue-100;
@import 'node_modules/handbook-ui/src/scss/handbook-ui-components'
```

You can start configuring the colors to suit your needs by first changing the `$brand-color` variable located in `src/scss/base/base.scss` from `$color-green-500` to `$color-indigo-500` or any other color you'd like.  There are lots of colors that can be found in the `src/scss/vars/colors.scss` file.

## CSS Only
Mustard is a CSS framework and does not include any javascript.  We do this in an effort to keep the filesize small.
You can use the framework as is or customize it via the component variables located at the top of each component scss file.

## Documentation
Full documentation is provided on our website located at [https://github.com/javanile/handbook-ui](https://github.com/javanile/handbook-ui).

## Become a Contributor
Handbook UI is provided free of cost because of the contributions that are made from developers like you. If you'd like to see this project grow, we would love it if you could submit a pull request to the project on GitHub.

**Clone the Repo or Fork and Install Dependencies:**
```bash
git clone https://github.com/javanile/handbook-ui.git
```

**Re-build the SCSS files:**
```
npm run build
```

**Open the Sandbox Environment:**
```
npm run dev
```

## Copyright and License
Powered by Francesco Bianco from Javanile.org.
Based on Mustard UI Copyright 2018 Kyle Logue.  
This project is licensed under the MIT License.
