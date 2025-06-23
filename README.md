# Library-Management-System
Task 1: Database Setup and Schema Design
Domain Selection
For this task, I choose the Library Management System domain.

Step 1: Identify Entities and Relationships
In a library management system, we can identify the following entities and their relationships:
1.Books Table:
   Attributes: BookID, Title, AuthorID, ISBN, PublishedYear, CategoryID
2.Authors Table:
  Attributes: AuthorID, Name, BirthDate
3.Categories Table:
  Attributes: CategoryID, CategoryName
4.Members Table:
  Attributes: MemberID, Name, Email, Phone, JoinDate
5.Loans Table:
  Attributes: LoanID, BookID, MemberID, LoanDate, ReturnDate
  
Relationships:
A book can have one author (1-to-many).
A book can belong to one category (1-to-many).
A member can borrow multiple books (1-to-many).
A loan record links a member to a book (many-to-many through Loans).

Step 2: Create Tables Using SQL
 Created Tables of Books, Authors, Categories,Members and Laons. And attched the MYSQL workbench File.

 Step 3: ER Diagram
  An ER diagram gives a better understanding of the overall database structure. It becomes easier to map the tables, their keys, and relationships. The ER diagram displays: Table structure along with the column names and their data types. Primary and foreign key constraints.

