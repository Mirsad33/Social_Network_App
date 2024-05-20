# Social_Network_App


This APP provides endpoints for managing users, thoughts, and reactions in a social network application. It is built using Express.js for routing and MongoDB with Mongoose ODM for database operations.

## Getting Started

To get started with this API, follow these steps:

1. Clone this repository to your local machine.
2. Install dependencies by running `npm install`.
3. Set up your MongoDB connection URI in the `.env` file.
4. Start the server by running `npm start`.

## API Endpoints

### Users

- `GET /api/users`: Get all users.
- `GET /api/users/:userId`: Get a single user by ID.
- `POST /api/users`: Create a new user.
- `PUT /api/users/:userId`: Update a user by ID.
- `DELETE /api/users/:userId`: Delete a user by ID.

### Friends

- `POST /api/users/:userId/friends/:friendId`: Add a friend to a user's friend list.
- `DELETE /api/users/:userId/friends/:friendId`: Remove a friend from a user's friend list.

### Thoughts

- `GET /api/thoughts`: Get all thoughts.
- `GET /api/thoughts/:thoughtId`: Get a single thought by ID.
- `POST /api/thoughts`: Create a new thought.
- `PUT /api/thoughts/:thoughtId`: Update a thought by ID.
- `DELETE /api/thoughts/:thoughtId`: Delete a thought by ID.

### Reactions

- `POST /api/thoughts/:thoughtId/reactions`: Add a reaction to a thought.
- `DELETE /api/thoughts/:thoughtId/reactions/:reactionId`: Remove a reaction from a thought.

## Walkthrough Video

[Link to Walkthrough Video](#)

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose ODM

## Author

[Mirsad Abedinoski](#) - [github.com/Mirsad33](#)
