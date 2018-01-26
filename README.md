# React Character Map

Include a character map in your app using our React Character Map.

It provides a simple interface for users to select a character from a list of categorised characters.

## Installation

```
npm install react-character-map
```

or
```
yarn add react-character-map
```


## Usage

```js
// Import the module into your react app
import {CharacterMap} from 'react-character-map';
```

```js
// Use the element;
<CharacterMap onSelect={function(char,e){ console.log(char, e); }} />
```


### Properties

The only property on the element is the `onSelect` callback. This is fired when the user clicks on a character.


### Styling
The package comes with very basic styling, it is recommended that you style it to match your app.


![](http://c.dayjo.me/0I2H0s0M0s2O/Screen%20Recording%202018-01-26%20at%2002.51%20pm.gif)
