# Toy Tales

Toy Tales is a React application that allows users to manage Andy's toy collection. Users can view toys, add new toys, like their favourite toys, and donate toys.

## Features

- **View Toys:** Fetches and displays all toys from the server.
- **Add Toys:** Allows users to add new toys with a name and image URL.
- **Like Toys:** Increases the like count when the Like button is clicked.
- **Donate Toys:** Removes a toy from the collection when the Donate button is clicked.

## Technologies Used

- React
- JavaScript
- CSS
- JSON Server
- Vite
- Vitest

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone git@github.com:Honorine01/react-hooks-toy-tales-vite.git
   ```

2. Navigate into the project directory:

   ```bash
   cd react-hooks-toy-tales-vite
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the JSON Server:

   ```bash
   npm run server
   ```

   The API runs at `http://localhost:3001`.

5. In another terminal, start the React application:

   ```bash
   npm run dev
   ```

   Open the local URL displayed in your terminal.

## Running Tests

To run the test suite:

```bash
npm run test
```

## API

The application uses JSON Server to manage toy data through the following endpoint:

`http://localhost:3001/toys`

The application uses:
- GET to fetch toys.
- POST to add toys.
- PATCH to update toy likes.
- DELETE to remove toys.