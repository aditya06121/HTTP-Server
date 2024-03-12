# HTTP Server in C

This project implements a simple HTTP server in C, allowing communication between clients and the server over the HTTP protocol. The server handles incoming HTTP requests, processes them, and sends appropriate HTTP responses back to the clients.

[HTTP Basics](./HTTP.md)

## Features

- Basic HTTP server functionality.
- Supports handling of GET requests.
- Sends HTML responses to clients.
- Simple and easy-to-understand codebase.

## Prerequisites

- C compiler (such as GCC)
- Basic knowledge of C programming
- Terminal or command prompt

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/aditya06121/HTTP-Server.git
   ```

2. Compile the server:

   ```bash
   gcc http_server.c -o http_server
   ```

3. Run the server:

   ```bash
   ./http_server
   ```

4. Access the server using a web browser or an HTTP client tool, such as cURL:

   ```bash
   curl http://localhost:8080
   ```

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.