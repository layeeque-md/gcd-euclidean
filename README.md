# GCD using Euclidean Algorithm

This module provides a function to calculate the Greatest Common Divisor (GCD) of two integers using the Euclidean algorithm.

## Installation

To install the module, use npm:

```sh
npm install gcd-euclidean
```

## Usage

```js
const gcd = require('gcd-euclidean');

console.log(gcd(4, 12)); // Output: 4
console.log(gcd(15, 25)); // Output: 5
console.log(gcd(7, 3)); // Output: 1
```

## Function

### `gcd(a, b)`

Calculates the GCD of two integers `a` and `b`.

#### Parameters

- `a` (number): The first integer.
- `b` (number): The second integer.

#### Returns

- (number): The GCD of `a` and `b`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.