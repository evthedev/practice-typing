# Types

An important of Typescript are types. Coming from a Javascript background, which is a weakly and dynamic typed language, that's often the hardest part to grasp. In this exercise, we will try to convert a pure Javascript object into a fully typed Typescript one.

## How it works

In this directory, there's four important files:

- package.json: It contains the basic packages required to make this work.
- tsconfig.json: Contains the basic configuration for the Typescript compiler. The solution should compile under this file.
- result.js: The file to convert
- test/result.js: A test file with the desired behaviour.

## How to work over it

1. Run `cp result.js result.ts`.
2. Modify `result.ts` to add the appropiate types.
3. Try to compile using `./node_modules/.bin/tsc`.
4. Run the tests and see if they pass!
