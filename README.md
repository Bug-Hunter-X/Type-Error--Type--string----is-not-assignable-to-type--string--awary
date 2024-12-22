# Type Error: Type 'string[]' is not assignable to type 'string'
This repository demonstrates a common type error in TypeScript where an array of strings is passed to a function expecting a single string.

## Bug
The `greeter` function expects a single string argument. However, the `user` variable is an array of strings.  This results in a type error when trying to pass `user` to `greeter`.

## Solution
The solution involves either modifying the `greeter` function to accept an array of strings or modifying the way `user` is handled to pass a single string to the function.