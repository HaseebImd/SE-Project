<h1>Software Engineering Fundamentals, CSC-2073</h1>
Assignment  <br>
<b>Make 6 following diagrams for given Case Study “Library Management System”, </b> <br>
  after problem statement, some points have been given for each
  <br>
diagram for your help.<br>
1. Class Diagram<br>
2. Use-Case Diagram<br>
3. Sequence Diagram<br>
4. Collaboration Diagram<br>
5. Activity Diagram<br>
6. State Chart Diagram<br>
Instructions for assignment submission:<br>
• Due date for assignment submission is in first lecture After<br><br>
Ramazan holidays<br>
• Submission will be in hard copy after binding<br>
• Presentation in ppt will also be given by every student in front of<br>
class, so copy and paste will reward you with zero scores<br><br>
• Late submission will not be acceptedCase Study
Library Management System<br>
Problem Statement:<br>
The case study titled Library Management System is library management software for the<br>
purpose of monitoring and controlling the transactions in a library. This case study on the library<br><br>
management system gives us the complete information about the library and the daily<br>
transactions done in a Library. We need to maintain the record of new s and retrieve the details<br>
of books available in the library which mainly focuses on basic operations in a library like adding<br><br>
new member, new books, and up new information, searching books and members and facility to<br>
borrow and return books. It features a familiar and well thought-out, an attractive user interface,<br>
combined with strong searching, insertion and reporting capabilities. The report generation<br>
facility of library system helps to get a good idea of which are ths borrowed by the members,<br>
makes users possible to generate hard copy.<br>
The following are the brief description on the functions achieved through this case study:<br>
End-Users:<br>
•Librarian: To maintain and update the records and also to cater the needs of the users.<br>
•Reader: Need books to read and also places various requests to the librarian.<br>
•Vendor: To provide and meet the requirement of the prescribed books.<br>
Class Diagram<br>
Classes identified:<br>
Library<br>
Librarian<br>
Books Database<br>
User<br>
Vendor<br>
Use-case DiagramActors vs Use Cases:<br><br>
Librarian<br>
•Issue a book<br>
•Update and maintain records<br>
•Request the vendor for a book<br>
•Track complaints<br>
User<br>
•Register<br>
•Login<br>
•Search a book<br>
•Request for isse<br>
•View history<br>
•Request to the Librarian<br><br>
•Unregister<br>
Books Database<br>
•Update records<br>
•Show books status<br>
Vendors<br>
•Provide books to the library<br>
•Payment acknowledgement<br>
Sequence Diagram<br>
Sequence diagram for searching a book and issuing it as per the request by the user from the<br><br>
librarian:<br>
Collaboration Diagram<br>
Collaboration Diagram for searching a book and issuing it as per the request by the user from<br>
the librarian:<br>
Activity DiagramActivities:<br>
User Login and Authentication<br>
Search book operation for Reader<br><br><br><br>
Acknowledge and Issue books to the users by the Librarian<br><br><br>
Provide books requested by the Librarian from the Vendor<br><br>
Bill payment from the Librarian to the Vendor<br>
Status of the books updated in the Books Database<br>
State Chart Diagram<br>
States:<br>
Authentication<br>
Successfully logged on or re-login<br>
Search for a book (user) / request the vendor (librarian) / provide the requested book (vendor)<br>
Receive acknowledgement<br>
Logged off / re-search / new function<br>
Transitions:<br>
Authenticate ---> Logged in<br>
Logged in ---> Search <---> Acknowledgement<br>
Logged in ---> Request Vendor <---> Provide Book <---> Acknowledgement<br>
Logged in ---> Provide Book <---> Acknowledgement<br><br>
Acknowledgement ---> Logged off<br>
