# Code Challenge 02

Insert and shift an array in middle at index

## Specifications
- Read all of these instructions carefully. Name things exactly as described.
- Do all your work in a public repository called `data-structures-and-algorithms`.
- Create a new branch in your repo called `array-shift`.
- Your top-level readme should contain a "Table of Contents" navigation to all of your challenges and implementations so far. (Don't forget to update it!)
- This assignment should be completed within the `challenges` subdirectory of the repository.
- On your branch, create...
    - _C#_: a new .NET Core console project named `ArrayShift`. Within your `Program.cs` create a new static method outside of `Main()` following the naming conventions below. Call your newly created method in `Main()` once complete.
    - _JavaScript_: a folder named `arrayShift` which contains a file called `array-shift.js`
    - _Python_: a folder named `array_shift` which contains a file called `array_shift.py`
    - _Java_: a file called `ArrayShift.java`
- Include any language-specific configuration files required for this challenge to become an individual component, module, library, etc.
    - _NOTE: You can find an example of this configuration for your course in your class lecture repository._

## Feature Tasks
- Write a function called `insertShiftArray` which takes in an array and the value to be added. Without utilizing any of the built-in methods available to your language, return an array with the new value added at the middle index.

## Example

| Input | Output |
|-----|----|
| `[2,4,6,8], 5` | `[2,4,5,6,8]` |
| `[4,8,15,23,42], 16` | `[4,8,15,16,23,42]` |

## Stretch Goal
Once you've achieved a working solution, write a second function that removes an element from the middle index and shifts other elements in the array to fill the new gap.

## Requirements
Ensure your complete solution follows the standard requirements. 

1. Write [unit tests](../../Challenge_Testing)
1. Follow the [template for a well-formatted README](../../Challenge_Documentation)
1. Submit the assignment following [these instructions](../SUBMISSIONS.md)
