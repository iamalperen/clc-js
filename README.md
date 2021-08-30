
[![version](https://img.shields.io/npm/v/clc-js.svg?style=flat-square)](http://npm.im/clc-js)
[![downloads](https://img.shields.io/npm/dm/clc-js.svg?style=flat-square)](http://npm-stat.com/charts.html?package=clc-js)
[![MIT License](https://img.shields.io/npm/l/clc-js.svg?style=flat-square)](http://opensource.org/licenses/MIT)


# Clc-js

clc.js is a lightweight math calculation library. 

This is an open-source javascript library for math calculations and computations. 

This library is pretty new, this README will be updated with new informations. 

For more math formulas and computations, please open issues.


# Usage

```sh
npm install clc-js
```

```js
var clc = require('clc.js');

// Calculation of distance between two points (x1,y1) <----> (x2,y2)
clc.calcDistBetween(3,5,6,1); // returns -> 5

// Calculation of Center coordinates of three points (x1,y1) (x2,y2) (x3,y3)
clc.calcCentroid(1,2,3,4,5,6) // returns -> {x: 3, y: 4}

// Calculation of area of circle by given radius
clc.calcAreaOfCircle(3) // returns -> 28.274333882308138

// Calculation of perimeter of circle by given radius
clc.calcPerimeterOfCircle(3) // returns -> 18.84955592153876

// Calculation of hypotenuse by given legs
clc.calcPythagorean(3,4) // returns -> 5

// Calculation of simplified interest rate
clc.calcSimplifiedInterest(5000,0.05,12); // returns -> 8979.281630110647

// Calculation of compound interest rate
clc.calcCompoundInterest(5000,0.05,2,12)  // returns -> 9043.629747912944

// Calculation of decimal to binary
clc.calcDecimal2Binary(24)  // returns -> '11000'

// Calculation of decimal to hexadecimal
clc.calcDecimal2Hex(14) // returns -> 'E'

// Calculation of logarithm
clc.calcLog(8,2) // returns -> 3

// Calculation of logarithm by base e
clc.calcLn(5) // returns -> 1.6094379124341003

// Calculation of area of square
clc.calcAreaOfSquare(4) // returns -> 16

// Calculation of factorial of a number
clc.calcFactorial(5) // returns -> 120

// Calculation of Permutation
clc.calcPermutation(5,2) // returns -> 20

// Calculation of Combination
clc.calcCombination(5,2) // returns -> 10


```

# Author and License
Created and maintained by [Alperen](https://github.com/iamalperen) under [MIT](LICENSE.md) License
