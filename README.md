# Cities Query REST API

Welcome to the Cities Query REST API documentation!

This repository contains the source code and documentation for a RESTful API that allows users to query information about cities around the world. The API provides various endpoints to retrieve data such as city names, population, country, and other relevant details.

## Endpoints

### GET /cities

Returns a list of all cities available in the database.

### GET /cities/{id}

Returns the details of a specific city identified by its ID.

### GET /cities/search?query={searchQuery}

Searches for cities based on a provided search query. The API will return matching cities that match the search criteria.

### POST /cities

Allows the creation of a new city in the database. Requires authentication and proper authorization.

### PUT /cities/{id}

Updates the information of an existing city identified by its ID. Requires authentication and proper authorization.

### DELETE /cities/{id}

Deletes a city from the database. Requires authentication and proper authorization.

## Technologies Used

- Node.js: A JavaScript runtime environment.
- Express.js: A web application framework for Node.js.
- MongoDB: A NoSQL database used to store city data.
- Mongoose: An Object-Data Modeling (ODM) library for MongoDB.
- JSON Web Tokens (JWT): Used for authentication and authorization.

## Getting Started

To run this API locally, follow these steps:

1. Clone the repository.
2. Install the required dependencies using `npm install`.
3. Set up the environment variables (e.g., database connection details, API keys).
4. Start the server using `npm start`.

Make sure to configure the necessary environment variables and have a MongoDB instance running to ensure proper functionality.

## Contribution

Contributions to this project are welcome! If you have any ideas, suggestions, or bug fixes, please feel free to open an issue or submit a pull request.

Happy querying!


