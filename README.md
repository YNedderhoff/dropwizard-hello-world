Run with

```
java -jar target/dropwizard-hello-world-1.0-SNAPSHOT.jar server hello-world.yml
```

Calling `http://localhost:8080/hello-world` responds with something like

```json
{
"id": 1,
"content": "Hello, Stranger!"
}
```

Calling `http://localhost:8080/hello-world?name=Stan+the+man` responds with something like

```json
{
"id": 43,
"content": "Hello, Stan the man!"
}
```

For dropwizard metrics, call `http://localhost:8081/`
