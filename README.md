# librarymanagementsystem
This is a simple Library Management System Project done by me where I've used Python-OOP and File Handling Concepts.This is my first Python project and it is beginner-friendly too.

Introduction:
The Personal Library Management System is a command-line application designed to help users manage their personal book collections efficiently. With the increasing number of books owned by individuals, it becomes essential to have a systematic way to organize, search, and maintain records of these books. This project utilizes Python programming language and object-oriented programming principles to create a user-friendly interface for managing a library.

Literature Review:
Library management systems have evolved significantly over the years, transitioning from manual record-keeping to automated systems. Previous studies have highlighted the importance of digital solutions in enhancing the efficiency of library management. Various systems have been developed, focusing on different aspects such as user interface design, database management, and file persistence. The use of JSON for data storage has been recognized for its simplicity and effectiveness in maintaining structured data. This project builds upon these concepts by implementing a straightforward command-line application that emphasizes usability and data persistence.

Methodology:
The development of the Personal Library Management System followed a structured approach:
1)Planning & Design: The project began with the design of two main classes: Book and Library. The Book class encapsulates the attributes of a book, while the Library class manages a collection of books and handles file operations.
2)Implementation: The application was implemented in Python, utilizing object-oriented programming principles. The Book class includes methods for initialization and string representation, while the Library class provides methods for adding, viewing, searching, updating, and deleting books. Data persistence is achieved through JSON file operations.
3)Testing: Each function was tested to ensure proper functionality, including error handling for invalid inputs and file operations. The application was verified for data persistence by closing and reopening the program.

Results:
The Personal Library Management System successfully meets the project requirements. Users can:
1)Add new books to their collection.
2)View all books in the library.
3)Search for books by title or author.
4)Update existing book details.
5)Delete books from the collection.
The application effectively saves and loads data from a JSON file, ensuring that the library's contents persist between sessions. User feedback indicated that the command-line interface is intuitive and easy to navigate.

