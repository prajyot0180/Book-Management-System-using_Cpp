# Book Management System
The Book Management System is a C++ project designed to manage a collection of books efficiently using a linked list as the primary data structure. This project also incorporates file separation for modularity and persistence, ensuring a clean and scalable design.

<h3>Features</h3>
1. Add a Book

- Add a new book with details such as name, author, price, rating, and category.
2. Modify Existing Entries

- Update the information of an already existing book in the linked list.
3. Delete a Book

- Remove a book from the system, ensuring proper memory management.
4. Search by Author

- Find all books written by a specific author.
5. Search by Book Name

- Locate a book by its title.
6. Show Books Category-wise

- Display all books grouped by categories, such as fiction, non-fiction, or science.
7. Sort Books by Price

- Sort books in ascending or descending order of their price.
8. Sort Books by Rating

- Organize books based on user-defined ratings.
9. Display All Books

- View the entire list of books, including all their details.
10. File Persistence

- Save the book list to a file to ensure data persistence.
- Load book data from the file when the program starts.
11. Additional Features (Optional Enhancements)

- Search by ISBN : Enable searches using a unique ISBN number.
- Track Availability : Add a status field to indicate whether a book is available or issued.
- Advanced Sorting : Support multi-criteria sorting, e.g., by rating and then by price.
- Export Data : Allow exporting book data to external files in formats like CSV.
- Import Data : Populate the linked list by importing book details from external files.

<br><h3>Technologies Used</h3>
- Language : C++
- Data Structure : Singly/Doubly Linked List
- File Handling : For data persistence and modularity, files are separated into : 

    1. main.cpp: Contains the program's entry point and the menu-driven interface.

    2. Book.h and Book.cpp: Header and source files for the Book class, encapsulating book properties and methods.

    3.BookManager.h and BookManager.cpp: Header and source files for the linked list operations and file handling logic.

<br><h3>How to Use</h3>
    
1. Clone the Repository

- Clone this repository to your local machine.
2. Compile the Code

- Use a C++ compiler (e.g., g++) to compile the program.
- Example : g++ main.cpp Book.cpp BookManager.cpp -o BookManagementSystem  
3. Run the Program

- Execute the compiled program and interact with the menu-driven interface to manage your book collection.
4. Save and Load
- Data is automatically saved to a file after each operation and loaded at the start of the program for continuity.

<br><h3>Project Structure</h3>
- BookManagementSystem/  
- ├── main.cpp          # Entry point of the application  
- ├── Book.h            # Header file for the Book class  
- ├── Book.cpp          # Implementation file for the Book class  
- ├── BookManager.h     # Header file for linked list operations  
- ├── BookManager.cpp   # Implementation file for linked list operations  
- ├── books_data.txt    # File for storing book data persistently  
- └── README.md         # Project documentation 

<br><h3>Future Enhancements</h3>

- Integration with a GUI using libraries like Qt or SFML.
- Enhanced file formats like JSON or XML for storing book data.
- Adding a user authentication system for library management.
