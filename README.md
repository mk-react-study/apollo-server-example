# Apollo Server

- https://www.apollographql.com/docs/apollo-server/getting-started/
- https://www.apollographql.com/docs/apollo-server/v1/servers/express/
- http://localhost:5011 This is graphql playground link

### Request

```
{
  books {
    title
    author
  }
}
```

### Response

```
{
  "data": {
    "books": [
      {
        "title": "Harry Potter and the Chamber of Secrets",
        "author": "J.K. Rowling"
      },
      {
        "title": "Jurassic Park",
        "author": "Michael Crichton"
      }
    ]
  }
}
```
