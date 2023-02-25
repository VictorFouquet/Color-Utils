# Color Utils

Simple util classes to handle color conversions and representations.

All objects can be imported from the ```dist/index.js``` file.

## Content

- Abstract color class
- RGBA color class
- HSLA color class
- Color converter class

The converter can currently perform :

- RGBA to HSLA
- RGBA to hex
- Hex to RGBA
- HSLA to RGBA

Color objects contain a util method to be formatted to a CSS string.

### Future updates

- Color objects should be instantiated from CSS strings
- Color objects should have a ```toArray``` method to retrieve their values in a number array.


## Development

### Requirements

```npm``` and ```node```

### Install

```npm install``` at the root folder of the repository

### Scripts

- ```test``` runs unit tests
- ```compile``` compiles TypeScript to ES6 (```dist``` is the output folder)
