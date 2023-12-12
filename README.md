# Simple Ruby HTTP Server

This is a minimalistic Ruby script that implements a simple HTTP server using the Ruby `socket` library. The server listens on port 9292 and responds to incoming HTTP requests by displaying the request lines in an HTML page.

## Usage

1. Make sure you have Ruby installed on your system.
2. Save the script to a file, for example, `simple_server.rb`.
3. Open a terminal and run the script:

    ```bash
    ruby simple_server.rb
    ```

4. The server will be ready to accept requests.

## Testing

You can test the server by making an HTTP request using a tool like `telnet` or a web browser. For example, using `telnet`:

```bash
telnet localhost 9292
```
## HTTP Request

GET / HTTP/1.1
Host: 127.0.0.1:9292
Connection: keep-alive
Accept: */*

## Response

The server will respond with an HTML page containing the received HTTP request lines. The response includes basic headers and information about the request.

## Notes

- This server is for educational purposes and is not intended for production use.
- To stop the server, press Ctrl + C in the terminal where the script is running.