# loopback4-example-websocket-app

This example integrate a resp [Loopback 4](https://loopback.io/doc/en/lb4/) application [(socket.io)](https://socket.io).

Based on:
* [@loopback/examples-todo](https://github.com/strongloop/loopback-next/tree/master/examples/todo)
* [raymondfeng/loopback4-example-websocket](https://github.com/raymondfeng/loopback4-example-websocket)

## Basic use

```
npm install
npm start
Open your browser to http://localhost:3000
```

## Routes examples
* /chat/{id:number} -> ChatControllerWs (socket.io connections)
* /todo -> TodoController (HTTP Requests)

## License

MIT

## Change Log

### 0.1.1 (2020-07-24)

#### Features

* WebSocketMetadata attribute name added
* bind of io instance and namespace to inject in other controllers.

### 0.1.1 (2020-07-24)

#### Features

* integration websocket controller booter 

### 0.1.0 (2020-07-24)

#### Features

* integration with websocket example [https://github.com/raymondfeng/loopback4-example-websocket](https://github.com/raymondfeng/loopback4-example-websocket) 
