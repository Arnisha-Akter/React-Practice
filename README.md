# React Application Practice

This repository contains a React application with multiple components and features. Let's break down the provided code and create a comprehensive README file.

## App Component

### `App` Component

The `App` component serves as the main component for the React application. It includes the following features:

- **Dynamic Actor Rendering**: The `nayoks` array is dynamically mapped to render a list of actors. Each actor is displayed using an `li` element.

- **Person Component**: The `Person` component is introduced to represent individuals, both actors and singers. It takes a `name` prop to display the person's name.

- **Singers List**: The `singers` array is mapped using the `Person` component, showcasing the reusability of components.

- **Friend Component**: A `Friend` component is added to display information about a friend, including their favorite movie and phone number. It is used twice to represent different friends.

- **Styling**: Basic styling is applied to components, and a `singerStyle` object is used to customize the styling of singer names.

## Components

### `Person` Component

Represents an individual with a name and optional `nayika` prop.

### `Friend` Component

Displays information about a friend, including their favorite movie (`movie`) and phone number (`phone`).

## Data

- `nayoks`: An array containing the names of actors.
- `singers`: An array of objects with singer names and their respective jobs.
- `number`: A constant with the value 5555.

## Usage

1. Clone the repository: `git clone [repository_url]`
2. Navigate to the project directory: `cd [project_directory]`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. Open your browser and visit `http://localhost:3000` to view the app.

## Additional Information

- The application demonstrates dynamic list rendering, reusability of components, and basic styling.

- Components such as `Person` and `Friend` showcase the flexibility of React components in rendering different information.

## Technologies Used

- React
- JavaScript (ES6+)
- CSS

## Credits

- This project was created by [Arnisha Akter].

