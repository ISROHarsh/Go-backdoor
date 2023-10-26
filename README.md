## Usage
1. Compile and run `main.go` on the server machine. Use the `-listen` flag to specify the port to listen on.
   ```sh
   go run main.go -listen <port>
   ```

2. Compile and run client.go on the target machine. It will automatically connect to the server.
   ```
   go run client.go
   ```
   Enter commands on the server-side to be executed on the target machine. The results of these commands will be sent back to the server.

## Important Note

This software is made for educational purposes only. It should be used responsibly and only on systems for which you have authorization. Unauthorized access and use may be illegal.

## License

This project is provided under the MIT License. See the [License](./LICENSE) file for details.
 
