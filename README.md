# Library Management System

## Overview
This project is a Library Management System built using JavaFX for the user interface and MySQL for the database. The system allows users to perform various actions such as adding, updating, deleting, searching, and sorting books in a library.


### Key Features:
  - **Display Books:** Load and display book data from the MySQL database.
  - **Insert New Books:** Add new records to the library database.
  - **Search for Books:** Search for books by title, author, or other criteria.
  - **Update Existing Records:** Edit book details like title, author, and publication year.
  - **Delete Books:** Remove books from the database.
  - **Sort Data:** Sort books based on different attributes like title or author.
    
### Technologies Used:
  - **JavaFX:** For the user interface.
  - **MySQL:** For the database backend.
  - **JDBC:** Java Database Connectivity to interact with MySQL.
  - **Maven:** For project dependency management.

### Getting Started

### Prerequisites
  - **Java 8 or later:** Make sure you have Java installed on your machine.
  - **MySQL:** MySQL server installed and running locally or on a remote server.
  - **JDBC Driver:** MySQL JDBC driver (mysql-connector-java) is required to establish a connection between Java and MySQL.

### Installation
  1. **Clone the repository:**
     ```bash
       git clone https://github.com/NuffSaid-Bore/Library-System.git
     ````
  2. **Create a MySQL database**
      - Create a table for books with the following schema:
     ```bash
         CREATE TABLE books (
          id INT AUTO_INCREMENT PRIMARY KEY,
          title VARCHAR(255) NOT NULL,
          author VARCHAR(255),
          publication_year INT
      );
     ````
  3. **Configure Database Connection:**
       - In the project, locate the configuration file where the database connection details are stored (usually in the code where Connection is created).
       - Modify the connection details such as the host, username, password, and database name.
  4. **Run the Project:**
     - Open the project in your IDE (e.g., IntelliJ IDEA, Eclipse, vs code).
     - Compile and run the Main class to launch the library management system.

### Usage
  - **Display Books:** Upon startup, the system will display all books from the database.
  - **Insert New Books:** Use the "Add Book" form to enter new book details and click "Submit" to insert them into the database.
  - **Search for Books:** Enter search criteria (e.g., title or author) in the search bar and hit "Search" to filter the books.
  - **Update Existing Books:** Select a book to edit, modify its details, and click "Update" to save the changes.
  - **Delete Books:** Select a book and click "Delete" to remove it from the database.
  - **Sort Data:** Use sorting options (by title, author, or year) to order the book list.

### Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and create a pull request.
  1. Fork the repository.
  2. Create a new branch for your feature or fix.
  3. Commit your changes.
  4. Push to your forked repository.
  5. Open a pull request for review.


### License
This project is open-source and available under the [MIT License](https://mit-license.org/).
