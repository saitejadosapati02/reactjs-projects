# React Calculator App

A simple and elegant calculator application built using React. It supports basic arithmetic operations and provides a user-friendly interface styled with modern CSS.

## Features

- Basic operations: Addition, Subtraction, Multiplication, Division

- Real-time result preview

- Input validation for operators

- Responsive and clean UI

- Styled using CSS variables

## Technologies Used

- React (Functional Components + Hooks)

- CSS (with variables and custom styling)

### Installation

- git clone https://github.com/yourusername/react-calculator.git
- cd react-calculator
  -npm install

## Running the App - npm start

Open http://localhost:3000 to view the calculator in the browser.

## How It Works

-The App.js file maintains two states: calc (input string) and result (live preview).

-updateCalc() updates input while validating operators.

-calculate() evaluates the full expression using JavaScript’s eval.

-deleteLast() removes the last character from the input.

## Styling

-Uses custom CSS variables like --primary, --dark, etc.

-Flexbox layout for responsive design

-Button styling for interactive experience
