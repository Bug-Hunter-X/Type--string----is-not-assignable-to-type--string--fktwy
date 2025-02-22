# Type 'string[]' is not assignable to type 'string'
This bug demonstrates a common type error in TypeScript where an array of strings is passed to a function expecting a single string.
The solution involves modifying the function to accept an array of strings or changing how the string array is handled.
## Bug
The `greeter` function expects a single string, but an array of strings is passed to it.
## Solution
The solution modifies the `greeter` function to accept an array of strings and concatenates them with a space in between.