# bookstore CRUD app


Create a book store CRUD application using Angular 10 plus based on the mockup provided in this repository. APIs needed to create the application is below

## API List

- POST https://615425f02473940017efac40.mockapi.io/books -  Create Book
payload
```sh
{
    title:"Eleven Minutes",
    author:"Paulo Choelo",
    language:"Portugeese",
    bookCoverPhoto:"https:/photoapp.com/path",
    price:"100.00"
}
```

- GET https://615425f02473940017efac40.mockapi.io/books -  Get Books
- GET https://615425f02473940017efac40.mockapi.io/books/:bookId   - Get Single book details


- POST https://615425f02473940017efac40.mockapi.io/books/:bookId-  Update  Book
payload
```sh
{
    title:"Eleven Minutes",
    author:"Paulo Choelo",
    language:"Portugeese",
    bookCoverPhoto:"https:/photoapp.com/path",
    price:"100.00"
}
```
- DELETE https://615425f02473940017efac40.mockapi.io/books/:bookId-  Delete Book

