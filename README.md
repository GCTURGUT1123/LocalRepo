# Project Title: Library Management System <br> <hr>
<h2>Design and implement a Library Management System in Java that incorporates the 
    following aspects:</h2> <br> <hr>
    <h3>Classes.</h3><br><hr>
    <h3><i><strong> library class:</strong></i></h3><br>
        <ul>Manages the overall system. </ul>
        <ul>Contains lists/arrays of books, members, and transactions. </ul>
        <ul>Methods to add/remove books, register members, handle transactions, and 
        display information.</ul>
    <h3><i><strong> book class:</strong></i></h3><br>
        <ul>Attributes: title, author, genre, availability, etc. </ul>
        <ul>Methods to update availability status, retrieve book details, etc. </ul>
        <ul>For inheritance: Consider potential subclasses like FictionBook and 
        NonFictionBook.</ul>
    <h3><i><strong> member class:</strong></i></h3><br>
        <ul> <li>Attributes: name, ID, borrowedBooks (a list of books currently borrowed).</li>
        <li>Methods to borrow/return books, display member details, etc.</li> </ul>
    <h3><i><strong> transaction class:</strong></i></h3><br>
        <ul>Attributes: book, member, transactionDate, transactionType (borrow/return).</ul>
        <ul>Methods to log transactions, retrieve transaction history, etc. </ul> <hr>
    <h3>Constructors:</h3><br> <hr>
        <ol>Implement default constructors and parameterized constructors for each class to 
        initialize their attributes upon object creation. </ol>
        <ol> Utilize constructors to set default values and ensure proper initialization of objects.</ol><hr>
    <h3>Overloading:</h3><br> <hr>
    <p>Overload borrowing methods in the Library class to handle different scenarios: </p>
        <ol> Borrowing by member ID and book ID.</ol>
        <ol> Borrowing by book title, author, or genre.</ol>
    <h3>Overridinging:</h3><br> <hr>
        <ol>Override the toString() method in each class to provide customized representations 
            when objects are printed or converted to strings. </ol>
        <ol>For instance, in the Book class, the toString() method could display all book details. </ol> <hr>
    <h3>Inheritance: </h3><br> <hr>
        <ol>Create subclasses of Book such as FictionBook and NonFictionBook.</ol>
        <ul>These subclasses can inherit common attributes/methods from the Book class and 
        introduce specific characteristics or behaviors. </ul>
    <h3>Functionality to Implement: </h3><br> <hr>
        <ol> <b>Add Books:</b> Library method to add new books to the inventory.  </ol>
        <ol><b>Register Members:</b> Library method to register new members with unique IDs.  </ol>
        <ol><b>Borrow/Return Books:</b> Methods in the Library and Member classes to handle book 
            transactions.  </ol>
        <ol><b> Display Information:</b> Methods to show available books, borrowed books, member 
            details, etc. </ol>
        <ol> <b>Search Functionality:</b> Methods to search for books by title, author, or genre. </ol>
        <ol><b> Transaction Logs:</b> Maintain logs of book transactions (borrowing/returning) for record
            keeping. </ol> <hr>
        <p>This project combines multiple aspects of object-oriented programming in Java, 
            challenging you to design a cohesive system that effectively manages a library's 
            functionalities while utilizing concepts like inheritance, overloading, overriding, and 
            constructors. </p><hr>
        <p><b>Sample output for the Library Management System in text format can provide an idea of 
            how the functionalities might work together.</b></p><hr>
        
