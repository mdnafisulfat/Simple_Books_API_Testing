# Simple_Books_API_Testing
This repository contains a Postman collection for testing the Simple Books API. The API allows you to view books, create and manage orders, and register API clients.

This project demonstrates API testing using Postman. The tests cover various endpoints provided by the Simple Books API, including book retrieval, order creation, and client registration.

URL- https://simple-books-api.glitch.me

Endpoints Tested - 

GET /status - Checks the status of the API.

GET /books - Retrieves a list of books.

GET /books/:bookId - Retrieves detailed information about a specific book.

POST /orders - Submits a new order. (Requires authentication)

GET /orders - Views all orders. (Requires authentication)

GET /orders/:orderId - Views a specific order. (Requires authentication)

PATCH /orders/:orderId - Updates an existing order. (Requires authentication)

DELETE /orders/:orderId - Deletes an existing order. (Requires authentication)

POST /api-clients/ - Registers an API client to obtain an access token.
