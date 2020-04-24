# Simple CRUD RESTful API made on Go
## Endpoints:
GET - __/api/books__ - returns a parsed JSON file with 2 default books\
GET - __/api/books/:id__ - returns a parsed JSON book item with that ID\
POST - __/api/books - takes an JSON file in body of the request with this interface
```
{
  "isbn": "string",
  "title": "string",
  "author": {
    "firstname": "string",
    "lastname": "string"
  }
} 
```
DELETE - __/api/books/:id__ - deletes a book with ID from params and returns new JSON with updated books
PIT - __/api/books/:id__ - takes an JSON file in body of the request as same interface above and returns that book.
