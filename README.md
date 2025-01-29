# OKAS Assignment Files

This repository contains the assignment files for OKAS. It includes code snippets and solutions for various JavaScript and backend development concepts.  All code examples are provided as `.txt` files.

## Contents

*   **JavaScript Fundamentals:**
    *   `promises.txt`: Demonstrates the use of Promises in JavaScript, including handling different states (pending, resolved, rejected) and chaining.
    *   `async_await.txt`: Shows how to use `async/await` for asynchronous operations, along with error handling using `try...catch`.
    *   `closures.txt`: Explains and provides examples of closures in JavaScript.
    *   `event_loop.txt`: Briefly explains the event loop mechanism in Node.js.
    *   `set_timeout_fix.txt`: Contains the corrected code to print numbers 0 to 4 using `setTimeout` and explains the issue with the original code.
    *   `callback_to_async.txt`: Converts a callback-based function to an `async/await` version.

*   **Backend Development (Node.js & Express):**
    *   `express_route.txt`: Implements an Express.js route handler for `POST /register` that accepts user data and returns a success message.
    *   `mongoose_schema.txt`: Defines a Mongoose schema and model for a `Product`.
    *   `mongodb_query.txt`: Contains a MongoDB query to find products in a specific category and price range, sorted by price.

## How to Use the Files

The files in this repository are provided as plain text (`.txt`) files.  You can view them directly in a text editor or IDE.

**JavaScript Files:**

To run the JavaScript code snippets (e.g., `promises.txt`, `closures.txt`):

1.  Copy the code from the `.txt` file.
2.  Create a new JavaScript file (e.g., `promises.js`).
3.  Paste the code into the new `.js` file.
4.  Make sure you have Node.js installed.
5.  Navigate to the directory containing the file in your terminal.
6.  Run the file using `node filename.js` (e.g., `node promises.js`).

**Express.js Application:**

To use the Express.js code (`express_route.txt`):

1.  Copy the code from the `.txt` file.
2.  Create a new JavaScript file (e.g., `express_route.js`).
3.  Paste the code into the new `.js` file.
4.  Make sure you have Node.js and npm (or yarn) installed.
5.  Navigate to the directory containing the file in your terminal.
6.  Install the required dependencies: `npm install express body-parser` (or `yarn add express body-parser`).
7.  Run the application: `node express_route.js`.

**MongoDB Query:**

To use the MongoDB query (`mongodb_query.txt`):

1.  Copy the query from the `.txt` file.
2.  You'll need a MongoDB server running.
3.  Use a MongoDB client (like the `mongo` shell or MongoDB Compass) to connect to your database.
4.  Paste and execute the query in the client.

## Notes

*   The code snippets provided are for illustrative purposes and might need to be adapted for a real-world application.
*   The Express.js example (`express_route.txt`) provides a basic structure. You would typically add input validation, password hashing, and database interaction in a production environment.
*   The MongoDB query assumes you have a collection named `products` with the appropriate fields.


## Author

RAMESH SURA
