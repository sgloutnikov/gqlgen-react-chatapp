# GraphQL gqlgen subscriptions example

The following is a chat application which uses GraphQL subscriptions to communicate in real-time between clients. 
The original client is part of the [this tutorial](https://www.youtube.com/watch?v=E3NHd-PkLrQ) and
the backend is rewritten in Golang with gqlgen.


### Start Server
```shell
cd server/
go run server.go
```

### Start Client
```shell
cd client/
yarn
yarn start
```

A client will be available on http://localhost:8080. Launch multiple clients in different windows to simulate a chat.

#### More Examples

- https://github.com/99designs/gqlgen/tree/master/_examples/chat
- https://outcrawl.com/go-graphql-realtime-chat
