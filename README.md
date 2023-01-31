# library
This application allows the library to switch to digital accounting of books

Possibilities of application:
- Registration of readers
- Add books
- Issue books
- Release books (after the reader returns the book back to the library).

###Start
- Connect to your DB and create tables (path:src/main/java/com/example/libraryBoot/util/library_db.sql)
- Run SpringBootApplication (path:src/main/java/com/example/libraryBoot/LibraryBootApplication.java)
- Enter http://localhost:8080/books in browser to see a list of books or add a new one
- Click on the name of the book to issue it to the reader or edit it
- Enter http://localhost:8080/people in browser to see a list of people or add a new one
- Click on the name of the person to see his list of books

### Stack
App include:
- Java  11
- Maven
- Spring Boot
- PostgreSQL
- Spring Data JPA
- Spring Web
