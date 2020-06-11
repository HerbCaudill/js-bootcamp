## Code challenges

#### Hello, world!

_console, editor, github, functions, if/then_

1. Write a function called `hello` that prints "Hello, world!" in the console.

   ```js
   function hello() {
       ...
   }

   hello()
   //  Hello, world!
   ```

1. Write a function that takes a name and prints "Hello, " followed by the name:

   ```js
   function hello(name) { ... }

   hello('Herb')
   //  Hello, Herb!
   ```

1. Write a function that takes two names and says hello to both of them:

   ```js
   function hello(name1, name2) { ... }

   hello('Herb', 'Georgi')
   // Hello, Herb and Georgi!
   ```

1. Write a function that takes one or two names. If two names are provided, say hello to both of them. Otherwise, say hello to just one.

   ```js
   function hello(name1, name2) {...}

   hello('Herb')
   // Hello, Herb!

   hello('Herb', 'Georgi')
   // Hello, Herb and Georgi!
   ```

#### Functions with numbers

_arrays, loops, functions calling functions_

1. Write a function that takes two numbers `a` and `b` and multiplies them together.

   ```js
   function multiply(a, b) { ... }

   multiply(3, 4)
   // 12
   ```

1. Write a function that takes an array of numbers and adds them all up.

   ```js
   function sum(arr) { ... }

   sum([234, 59253, 12])
   // 59499
   ```

1. Write a function that takes an array of numbers and returns the average.

   ```js
   function average(arr) { ... }

   average([5, 7, 12])
   // 8
   ```

1. Write a function that takes an array of numbers and returns the largest number.

   ```js
   function max(arr) { ... }

   max([17, 24, 32, 5, 155, 77])
   // 155
   ```

#### Even/odd

_modulo, array methods_

1. Write a function named `isEven` that takes a number and returns `true` if it is even, `false` if it is odd.

   ```js
   function isEven(n) { ... }

   isEven(5)
   // false
   isEven(12423578)
   // true
   ```

1. Write a function `isOdd` that takes a number and returns `true` if the number is odd, `false` if it is even. Use the `isEven` function inside `isOdd`.

1. Write a function named `allAreEven` that takes an array of numbers and returns `true` if **all** the numbers in the array are even.

1. Write a function named `someAreEven` that takes an array of numbers and returns true if **at least one** of the numbers in the array are even.

1. Write a function named `evenPercentage` that takes an array of numbers and returns the percentage of numbers in the array that are even.

#### Divisibility

_refactoring; objects_

1. Write a function that tells if a number is divisible by 3.

   ```js
   function isDivisibleBy3(n) { ... }

   isDivisibleBy3(27)
   // true
   isDivisibleBy3(25)
   // false
   ```

1. Write a function that tells if a number is divisible by 5.

1. Write a function that takes two numbers, `n` and `d`, and tells if `n` is divisible by `d`.

   ```js
   function isDivisible(n, d) { ... }

   isDivisible(27, 3)
   // true
   isDivisible(25, 5)
   // true
   isDivisible(25, 3)
   // false
   ```

1. Refactor `isDivisibleBy3` and `isDivisibleBy5` so that they use the general `isDivisible` function internally.

1. Write a function that tells if a number is prime, using the sieve of Eratosthenes.

#### Simple game

"Guess my number"

## Final project

"Concentration" game
