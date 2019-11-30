# react-tab-visbility

use react-tab-visibility, if you need tab active or inactive informations.

You get a bool for visibility state and number for hidden duration

## example

supports react 15.x and 16.x

## install

```
> npm install react-tab-visibility --save
```

## how to use

```jsx
import TabVisibility from 'react-tab-visibility';

class YourComponent extends TabVisibility {
    onTabVisibilityChange(status) {
        status = {
            isTabVisible: Boolean,
            hiddenTime: Number // seconds
        }
    }
}
```

### Get information about active or inactive tab

create in your parent class a new method to get change information

```js
onTabVisibilityChange(status) {
    status = {
        isTabVisible: Boolean,
        hiddenTime: Number // seconds
    }
}
```

or check for following state variables

```js
this.state = {
    tabIsVisible: true,
    hiddenTime: 0
};
```

### Development

if you want to add or optimize this component, feel free <3

clone this repository and run install

```
npm install --save
```

start dev server

```
npm start
```

make your changes and build new es5 friendly version

```
npm run build
```

## Give me a coffee

[![Donate](https://img.shields.io/badge/donate-%20%E2%9D%A4%20-green.svg)](https://www.paypal.me/schauf)

[get in touch?](http://www.holger-schauf.de)
