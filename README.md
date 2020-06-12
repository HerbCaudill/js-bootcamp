1.  Write a program that prints "Hello, world!" in the console.

    ```
    Hello, world
    ```

2.  Write a program that asks for a name and prints "Hello, " followed by the name.

    ```
    What is your name? > Baird
    Hello, Baird
    ```

3.  Write a program that asks for a first name and last name, and prints out "Hello," followed by
    the full name. (Use string interpolation..

    ```
    What is your first name? > Baird
    What is your last name? > Caudill
    Hello, Baird Caudill
    ```

4.  Write a program that requests two numbers `a` and `b` and multiplies them together.

    ```
    Enter a number > 4
    Enter another number > 7
    4 x 7 is 28
    ```

5.  Write a program tells you if you're old enough to vote.

    ```
    How old are you? > 20
    Where are you from? (US or Spain. > US
    You are not old enough to vote
    ```

6.  Write a program to convert from Fahrenheit and vice versa.

    ```
    Enter the temperature: > 23
    F or C? > C
    23⁰C is 73⁰F
    ```

7.  Write a function that returns a random number between 1 and 10.

8.  Write a function that returns a random 4-digit number.

9.  Make a "Guess My Number" game.

    ```
    I'm thinking of a number between 1 and 100.
    Can you guess my number? > 50
    Too high!
    Can you guess my number? > 25
    Too low!
    Can you guess my number? > 31
    You guessed my number!!!
    ```

10. Write a function that rolls two dice and shows the outcome graphically:

    ```
    ┌───────┐   ┌───────┐
    │ ●   ● │   │     ● │
    │   ●   │   │   ●   │
    │ ●   ● │   │ ●     │
    └───────┘   └───────┘
    ```

11. adfs

12. Write a `sum` function that takes an array of numbers and adds them all up.

    ```js
    sum([3, 7, 12]) // 22
    ```

13. Write a test to confirm that the `sum` function works correctly.

    ```js
    expect(sum([3, 7, 12])).toEqual(22)
    ```

    > **Note:** All subsequent challenges must include passing tests.

14. Write an `average` function that takes an array of numbers and returns the average. (Hint: Use
    the `sum` function within the `average` function.)

    ```js
    average([5, 8, 14]) // 9
    ```

15. Write a function named `isEven` that takes a number and returns `true` if it is even, `false` if
    it is odd.

    ```js
    isEven(4) // true
    isEven(2341) // false
    ```

16. Write a function `isOdd` that takes a number and returns `true` if the number is odd, `false` if
    it is even. Use the `isEven` function inside `isOdd`.

    ```js
    isOdd(4) // false
    isOdd(2341) // true
    ```

17. Write a function that takes an array of numbers and returns `true` if **all** the numbers in the
    array are even.

    ```js
    allAreEven([3, 5, 7]) // false
    allAreEven([2, 3, 4]) // false
    allAreEven([4, 8, 16]) // true
    ```

18. Write a function named that takes an array of numbers and returns true if **at least one** of
    the numbers in the array are even.

    ```js
    someAreEven([3, 5, 7]) // false
    someAreEven([2, 3, 4]) // true
    someAreEven([4, 8, 16]) // true
    ```

19. Write a function that tells if a number is divisible by 3.

    ```js
    isDivisibleBy3(18) // true
    isDivisibleBy3(20) // false
    ```

20. Write a function that tells if a number is divisible by 5.

    ```js
    isDivisibleBy5(18) // false
    isDivisibleBy5(20) // true
    ```

21. Write a function that takes two numbers, `n` and `d`, and tells if `n` is divisible by `d`.
    Refactor the previous four functions so that they use the general `isDivisible` function
    internally.

22. Write a function that takes a temperature in Fahrenheit, and returns an object with that temperature in Fahrenheit, Celsius, and Kelvin.

    ```
    Enter temperature in F: > 74
    {
       fahrenheit: 74
       celsius: 23
       kelvin: 296
    }

    ```

23) Write a function that takes a list of to-do items, and prints them to the console, along with
    checkboxes indicating whether they've been completed or not.

    ```
    [ ] Play with the cat
    [√] Do the dishes
    [ ] Empty litter boxes
    ```

24) First write tests for a function that tells if a number is prime; then write the function
    itself, using the sieve of Eratosthenes.

    ```js
    expect(isPrime(12)).toBe(false)
    expect(isPrime(37)).toBe(true)
    ```

25) Write a function that prints out the first N numbers in Fibonacci's sequence.

    ```
    How many numbers? > 10

    0 1 1 2 3 5 8 13 21 34 55
    ```

26) Write a function that returns the factorial of the given number.

    ```
    Enter a number: > 43
    43! = 60415263063373835637355132068513997507264512000000000
    ```

27) Write a program that prints out Pascal's Triangle for a given number of rows.

    ```
    How many rows? > 6

    1
    1   1
    1   2   1
    1   3   3   1
    1   4   6   4   1
    1   5  10   0   5   1
    ```

#### Final project
