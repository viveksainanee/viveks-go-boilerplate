## Go Boilerplate - Gin

This boilerplate can be used for easy prototyping of new projects.

To query the API, you can use this curl command or use the included Postman collection.

```sh
curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```

### Further Reading
- https://gin-gonic.com/docs/
- https://go.dev/doc/tutorial/web-service-gin
