# OKAS Assignment Files

This repository contains the assignment files for OKAS.  It includes code snippets and solutions for various JavaScript and backend development concepts.

## Contents

*   **JavaScript Fundamentals:**
    *   `promises.js`: Demonstrates the use of Promises in JavaScript, including handling different states (pending, resolved, rejected) and chaining.
    *   `async_await.js`: Shows how to use `async/await` for asynchronous operations, along with error handling using `try...catch`.
    *   `closures.js`: Explains and provides examples of closures in JavaScript.
    *   `event_loop.js`: Briefly explains the event loop mechanism in Node.js.
    *   `set_timeout_fix.js`: Contains the corrected code to print numbers 0 to 4 using `setTimeout` and explains the issue with the original code.
    *   `callback_to_async.js`: Converts a callback-based function to an `async/await` version.

*   **Backend Development (Node.js & Express):**
    *   `express_route.js`: Implements an Express.js route handler for `POST /register` that accepts user data and returns a success message.
    *   `mongoose_schema.js`: Defines a Mongoose schema and model for a `Product`.
    *   `mongodb_query.js`: Contains a MongoDB query to find products in a specific category and price range, sorted by price.

## How to Run

To run the JavaScript files (e.g., `promises.js`, `closures.js`):

1.  Make sure you have Node.js installed.
2.  Navigate to the directory containing the file in your terminal.
3.  Run the file using `node filename.js` (e.g., `node promises.js`).

To run the Express.js application (`express_route.js`):

1.  Make sure you have Node.js and npm (or yarn) installed.
2.  Navigate to the directory containing the file in your terminal.
3.  Install the required dependencies: `npm install express body-parser` (or `yarn add express body-parser`).
4.  Run the application: `node express_route.js`.

For the MongoDB query (`mongodb_query.js`), you'll need a MongoDB server running.  You can then use a MongoDB client (like the `mongo` shell or MongoDB Compass) to execute the query against your database.

## Notes

*   The code snippets provided are for illustrative purposes and might need to be adapted for a real-world application.
*   The Express.js example (`express_route.js`) provides a basic structure.  You would typically add input validation, password hashing, and database interaction in a production environment.
*   The MongoDB query assumes you have a collection named `products` with the appropriate fields.

## Author

RAMESH SURA
