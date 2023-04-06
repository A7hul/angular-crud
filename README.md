# Book Management App
This is a simple Angular application that allows users to manage books in a library. Users can view a list of books, add a new book, edit an existing book, and delete a book.

## Getting Started
To get started with this project, follow these steps:

1. Clone the repository to your local machine using the command:

`git clone https://github.com/A7hul/angular-crud.git`

2. Install the necessary dependencies by running:

`npm install`
3. Start the development server by running:

`ng serve`
4. Open a web browser and navigate to http://localhost:4200 to view the application.

## Application Structure
The application consists of the following components:

- AppComponent - the main component that contains the navigation menu and router outlet.
- BookListComponent - displays a list of all the books in the library.
- BookAddEditComponent - allows users to add a new book or edit an existing one.
- BookDeleteComponent - displays a confirmation dialog when the user wants to delete a book.
The application also contains the following services:

- BookService - provides methods to interact with the REST API to retrieve, add, update, and delete books.
- CoreService - provides a method to display a snackbar message.
## Dependencies
This application uses the following dependencies:

- Angular Material - for styling and UI components.
- Angular Forms - for form validation and management.
- Angular HttpClient - for making HTTP requests to the REST API.
## REST API
This application relies on a REST API to manage books. The API endpoints are defined as follows:

- GET /books - returns a list of all the books in the library.
- POST /books - adds a new book to the library.
- GET /books/:id - returns the book with the specified ID.
- PUT /books/:id - updates the book with the specified ID.
- DELETE /books/:id - deletes the book with the specified ID.
