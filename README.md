# apollo-server
Apollo Server

* https://www.apollographql.com/docs/apollo-server/getting-started/
* http://localhost:5011

`Request`
```
{
  books {
    title
    author
  }
}
```

`Response`
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
