# To-Do Goals Project

This repo is a code-along project for the React & Redux Course of the [React Nanodegree program](https://www.udacity.com/course/react-nanodegree--nd019).

Most of the commits in this repository correspond to videos in the program.

## State Rules

1. Only an event can change the state of the store
2. The function that returns the new state needs to be a pure function

## What are Pure Functions

Pure functions are integral to how state in Redux applications is updated. By definition, pure functions:

1. Return the same result if the same arguments are passed in
2. Depend solely on the arguments passed into them
3. Do not produce side effects

## Functions Returning Functions 💡

Redux middleware leverages a concept called higher-order functions. A higher-order function is a function that either:

* accepts a function as an argument
* returns a function

Higher-order functions are a powerful programming technique that allow functions to be significantly more dynamic. You've actually already written a higher-order function in this course. The createRemoveButton() function is a higher-order function because the onClick parameter is expected to be a function (because onClick is set up as an event listener callback function.

For a refresher on higher-order functions, feel free to check out Lesson 2 in [Object-Oriented JavaScript](https://www.udacity.com/course/object-oriented-javascript--ud711).

## Project Setup

1. Clone the Project - git clone https://github.com/udacity/reactnd-redux-todos-goals.git
2. Go into the directory where the project now lives - `cd reactnd-redux-todos-goals`
3. Install the dependencies - `yarn install`
4. Start the app - `yarn start`

## Contributing

Because this is a code-along project and the commits correspond to specific videos in the program, we will not be accepting pull requests.

If you feel like there's a major problem, please open an issue to discuss the problem and potential resolution.