# File Service with gRPC

This project implements a file service using gRPC for efficient communication. It includes both synchronous and asynchronous implementations for retrieving files.

## Features

- **Synchronous File Retrieval**: Retrieve files synchronously using gRPC.
- **Asynchronous File Retrieval**: Retrieve files asynchronously for better performance.
- **File Streaming**: Stream large files in chunks.

## Requirements

- **gRPC**: Ensure gRPC and Protocol Buffers are installed.
- **C++11 or Later**: Compile with C++11 or a later standard.

## Build Instructions

1. Clone the repository.
2. Run `mkdir build && cd build`.
3. Execute `cmake ..`.
4. Build with `cmake --build .`.

## Run the Server and Client

1. Run the server with `./src/file_service_server`.
2. Run the client with `./src/file_service_client`.

## Contributing

Contributions are welcome. Please submit pull requests with detailed explanations.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
