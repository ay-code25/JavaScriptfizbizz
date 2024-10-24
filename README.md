
# FizzBuzz Project

This is a simple JavaScript project that implements the classic "FizzBuzz" coding challenge.

## Problem Statement

Given an integer input `num`, print every integer from 1 to that number. However:

- If the number is divisible by 3, print "Fizz" instead of the number.
- If the number is divisible by 5, print "Buzz" instead of the number.
- If the number is divisible by both 3 and 5, print "FizzBuzz".

## Project Setup

To run this project, you need to have a JavaScript runtime (such as a web browser or Node.js) installed.

### Code Example

Here is the main code of the project:

```javascript
function fizzBuzz(num){
  // Loop from 1 to the provided number
  for(let i = 1; i<=num; i++){
    // Check for divisibility by both 3 and 5
    if(i % 3 === 0 && i % 5 === 0){
      console.log('FizzBuzz');
    }
    // Check for divisibility by 3
    else if(i % 3 === 0){
      console.log('Fizz');
    }
    // Check for divisibility by 5
    else if(i % 5 === 0){
      console.log('Buzz');
    }
    // If not divisible by either, print the number
    else {
      console.log(i);
    }
  }
}

// Example usage:
fizzBuzz(5);  // Output: 1, 2, Fizz, 4, Buzz
fizzBuzz(15); // Output: FizzBuzz at 15 and other results
```
![image](https://github.com/user-attachments/assets/1c7ff689-1167-44d8-9d9d-4488e4f64e39)

## Usage

1. Copy the `fizzBuzz` function into your project or console.
2. Call the function with a number as an argument, such as `fizzBuzz(15)`.
3. The output will be printed in the console.

### Example Output

For `fizzBuzz(15)`, the output will be:

```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```

## How It Works

- The `for` loop iterates from `1` to `num`.
- Inside the loop, it checks if the number is divisible by both 3 and 5 (using the modulo operator `%`). If so, it prints "FizzBuzz".
- If the number is divisible only by 3, it prints "Fizz", and if it's divisible only by 5, it prints "Buzz".
- If none of the conditions match, it prints the number itself.

## Future Improvements

- Accept user input through an HTML form.
- Implement the solution in other programming languages (Python, C++, etc.).

---

## License

This project is open-source and free to use.

