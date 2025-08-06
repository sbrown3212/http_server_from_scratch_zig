# http_server_from_scratch_zig

Basic HTTP server made for learning purposes - Guided project from [ch.7](https://pedropark99.github.io/zig-book/Chapters/04-http-server.html) of "Introduction to Zig"

Upon running `zig run src/main.zig`, a server will be running on `port 3490` of localhost (127.0.0.1). The server responds with a simple page that return "Hello, World!" in an `<h1>`. Only the `GET` method is supported.
