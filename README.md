Hello SIR 

This project is a simple backend REST API built with Node.js, Express, and MongoDB. It allows users to manage student records through standard CRUD Create, Read, Update, Delete operations.

How It Works
Database Connection: The server reads configuration values from .env and connects to MongoDB before accepting any requests.

Data Handling: incoming JSON bodies are parsed automatically by Express and validated against the Mongoose schema.

Error Management: Malformed IDs or missing records return standard HTTP error codes (400 Bad Request or 404 Not Found). Internal server errors return a clean 500 response without exposing backend code traces.
