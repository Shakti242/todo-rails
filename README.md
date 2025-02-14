# Todo Rails

## Description

A simple TODO application built using Ruby on Rails and React to manage daily tasks efficiently.

## Features

- Create, read, update, and delete (CRUD) todos
- Mark todos as completed or pending
- RESTful API endpoints
- PostgreSQL database support
- Interactive frontend built with React.js

## Tech Stack

- **Backend:** Ruby on Rails
- **Database:** PostgreSQL
- **Frontend:** React.js

## Prerequisites

Make sure you have the following installed:

- Ruby (>= 3.0.0)
- Rails (>= 7.0.0)
- PostgreSQL
- Node.js & Yarn (for frontend)

## Installation

```sh
git clone https://github.com/yourusername/todo-rails.git
cd todo-rails
bundle install
rails db:create db:migrate
rails server
```

Your Rails API should now be running at [http://localhost:3000](http://localhost:3000).

Next, set up the React frontend:

```sh
cd frontend
npm install
npm start
```

Your React app should now be running at [http://localhost:3001](http://localhost:3001).

## API Endpoints

| Method | Endpoint     | Description         |
| ------ | ------------ | ------------------- |
| GET    | `/todos`     | Get all todos       |
| POST   | `/todos`     | Create a new todo   |
| GET    | `/todos/:id` | Get a specific todo |
| PUT    | `/todos/:id` | Update a todo       |
| DELETE | `/todos/:id` | Delete a todo       |

## Running Tests

To run tests, use:

```sh
rails test
```

## Deployment

For deployment on Heroku or Render:

```sh
git push heroku main
```

For frontend deployment:

```sh
cd frontend
npm run build
```

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m "Added new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the LICENSE file for details.
 
