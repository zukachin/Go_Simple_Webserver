# Go Simple Webserver

This project demonstrates how to create a simple web server using Go. The server serves static HTML files and handles a simple form submission.

## Files

- `server.go`: The main Go server file.

Create these html files.
- `index.html`: A static homepage.
- `form.html`: A simple form page.

## Running the Server

To run the server, follow these steps:

1. Build the Go server:
    ```sh
    go build
    ```

2. Run the server:
    ```sh
    go run server.go
    ```

3. If prompted by your firewall, allow the connection.

## Accessing the Server

Open your browser and visit the following URLs:

1. Homepage:
    ```
    http://localhost:8080/
    ```

2. Home route:
    ```
    http://localhost:8080/home
    ```

3. Form page:
    ```
    http://localhost:8080/form.html
    ```



