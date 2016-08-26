# go-websocket-example

Simple WebSocket server/client implementation in which the client is updated with the current date/time every second.

Based heavily on the example given here: https://github.com/gorilla/websocket/tree/master/examples/filewatch

    $ go get github.com/gorilla/websocket
    $ go install github.com/jlubawy/go-websocket-example
    $ go-websocket-example  # will start server on port 80
    $ # open index.html (had to allow all origins since not serving HTML)
