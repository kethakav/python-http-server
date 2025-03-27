# Python HTTP Server

This is a simple HTTP server implemented in Python. It serves static files and demonstrates basic HTTP request handling.

## Features

- Serves static HTML files (`index.html`, `hello.html`, etc.).
- Handles HTTP `GET` requests.
- Returns appropriate HTTP status codes (`200 OK`, `404 Not Found`, `501 Not Implemented`).
- Dynamically determines the MIME type of files using Python's `mimetypes` module.
