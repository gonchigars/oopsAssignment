
Library Management System Assignment

Objective:
Create a simple Library Management System using Java, demonstrating OOP concepts such as inheritance, interfaces, polymorphism, and encapsulation.

Components to Implement:

1. Item (Abstract Class):
   - Properties: itemId, title, author, publicationYear
   - Abstract method: calculateLateFee(int daysLate)

2. Book (Class extending Item):
   - Additional property: ISBN
   - Implement calculateLateFee method

3. Magazine (Class extending Item):
   - Additional property: issueNumber
   - Implement calculateLateFee method

4. DVD (Class extending Item):
   - Additional property: duration (in minutes)
   - Implement calculateLateFee method

5. Borrowable (Interface):
   - Methods: checkOut(), returnItem(), isAvailable()

6. Reservable (Interface):
   - Methods: reserve(), cancelReservation()

7. LibraryMember (Class):
   - Properties: memberId, name, contactInfo
   - Methods to borrow and return items

8. Librarian (Class extending LibraryMember):
   - Additional methods to add and remove items from the library

9. Library (Class):
   - Manages collections of items, members, and librarians
   - Methods to add/remove items, register members, and process checkouts/returns

10. LibraryManagementSystem (Main class):
    - Demonstrate the functionality of the system

Requirements:

1. Implement all classes and interfaces mentioned above.
2. Use appropriate access modifiers (public, private, protected) for class members.
3. Implement method overriding where applicable.
4. Use polymorphism in the Library class when dealing with different types of items.
5. Implement proper exception handling for operations like checking out unavailable items.
6. Add Javadoc comments for classes and important methods.

Bonus Tasks:

1. Implement a search functionality in the Library class to find items by title or author.
2. Add a fine calculation system for overdue items.
3. Implement a basic command-line interface for user interaction with the system.

Deliverables:

1. Java source files for all classes and interfaces.
2. A main class (LibraryManagementSystem) demonstrating the usage of the implemented classes.
3. A brief document explaining your design decisions and any challenges faced.

Evaluation Criteria:

1. Correct implementation of OOP concepts (inheritance, interfaces, polymorphism, encapsulation).
2. Code organization and clarity.
3. Proper error handling and input validation.
4. Adherence to Java naming conventions and best practices.
5. Completeness of the implemented functionality.

This assignment covers similar OOP concepts as the blog application but in a different context, allowing students to apply their knowledge to a new problem domain. It includes opportunities for implementing inheritance hierarchies, interfaces, polymorphism, and encapsulation in a practical scenario.
