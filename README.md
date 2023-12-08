# React Application README

## App Component

### `App` Component

This React application consists of two primary components: `ExternalUsers` and `Counter`. The application fetches external user data from the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) API and displays user information. Additionally, there is a simple counter component with buttons to increase and decrease the count.

#### Usage

```javascript
import logo from './logo.svg';
import './App.css';
import { useEffect, useState } from 'react';

function App() {
  return (
    <div className="App">
      {/* <Counter></Counter> */}
      <ExternalUsers></ExternalUsers>
    </div>
  );
}

# JavaScript Basics

This repository contains a set of basic JavaScript examples covering fundamental concepts such as JSON manipulation, array operations, conditional statements, loops, functions, and object handling.

## JSON Manipulation

### 1. JSON - stringify, parse

```javascript
const student = {
    name: 'Salib Khan',
    age: 32,
    movies: ['king khan', 'Dhakar Mastan']
}
const studentJSON = JSON.stringify(student);
const studentObj = JSON.parse(studentJSON);

## Getting Started

To run this application locally, follow these steps:

1. Clone the repository: `git clone [repository_url]`
2. Navigate to the project directory: `cd countries-react-app`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. Open your browser and visit `http://localhost:3000` to view the app.

## Technologies Used

- React
- JavaScript (ES6+)
- CSS

## Credits

- This project was created by [Your Name].

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as needed. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

Enjoy exploring information about different countries with this React app!
