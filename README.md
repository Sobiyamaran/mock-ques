# mock-ques
Data structures:
1.What are the various operations that can be performed on different Data Structures?
Insertion ? Add a new data item in the given collection of data items. Deletion ? Delete an existing data item from the given collection of data items. Traversal ? Access each data item exactly once so that it can be processed. Searching ? Find out the location of the data item if it exists in the given collection of data items. Sorting ? Arranging the data items in some order i.e. in ascending or descending order in case of numerical data and in dictionary order in case of alphanumeric data.

4. Applications of Stack:
Balancing symbols
Infix to Postfix Conversion using Stack
Evaluation of Postfix Expression
Implementing function call (including recursion)
Reverse a String using Stack
Page visited history in a web browser[Back Buttons]
Undo sequence in text editor
Matching tags in HTML and XML
Implement two stacks in an array
Check for balanced parentheses in an expression
2. How is an Array different from Linked List?
The size of the arrays is fixed, Linked Lists are Dynamic in size. Inserting and deleting a new element in an array of elements is expensive, Whereas both insertion and deletion can easily be done in Linked Lists. Random access is not allowed in Linked Listed. Extra memory space for a pointer is required with each element of the Linked list. Arrays have better cache locality that can make a pretty big difference in performance.

3. What is Stack and where it can be used?
Stack is a linear data structure which the order LIFO(Last In First Out) or FILO(First In Last Out) for accessing elements. Basic operations of the stack are: Push, Pop, Peek

4. How to implement a queue using stack?
A queue can be implemented using two stacks. Let queue to be implemented be q and stacks used to implement q be stack1 and stack2. q can be implemented in two ways:

Method 1 (By making enQueue operation costly) Method 2 (By making deQueue operation costly)

5. What is a Queue, how it is different from the stack and how is it implemented?
Queue is a linear structure that follows the order is First In First Out (FIFO) to access elements. Mainly the following are basic operations on queue: Enqueue, Dequeue, Front, Rear The difference between stacks and queues is in removing. In a stack we remove the item the most recently added; in a queue, we remove the item the least recently added. Both Queues and Stacks can be implemented using Arrays and Linked Lists.

6. How to implement a stack using queue?
A stack can be implemented using two queues. Let stack to be implemented be ‘s’ and queues used to implement be ‘q1’ and ‘q2’. Stack ‘s’ can be implemented in two ways:

Method 1 (By making push operation costly) Method 2 (By making pop operation costly) See Implement Stack using Queues ........ ........

7. What is a primary key?
A primary key is a combination of fields which uniquely specify a row. This is a special kind of unique key, and it has implicit NOT NULL constraint. It means, Primary key values cannot be NULL.

8. What is normalization?
Normalization is the process of minimizing redundancy and dependency by organizing fields and table of a database. The main aim of Normalization is to add, delete or modify field that can be made in a single table. [1/24, 14:08] Jeyan Anna: Database:

9.What is SQL?
SQL stands for Structured Query Language , and it is used to communicate with the Database. This is a standard language used to perform tasks such as retrieval, updation, insertion and deletion of data from a database. Standard SQL Commands are Select.

10. What is a query?
A DB query is a code written in order to get the information back from the database. Query can be designed in such a way that it matched with our expectation of the result set. Simply, a question to the Database.

11. What is a trigger?
A DB trigger is a code or programs that automatically execute with response to some event on a table or view in a database. Mainly, trigger helps to maintain the integrity of the database.

Example: When a new student is added to the student database, new records should be created in the related tables like Exam, Score and Attendance tables.

12. What is the difference between DELETE and TRUNCATE commands?
DELETE command is used to remove rows from the table, and WHERE clause can be used for conditional set of parameters. Commit and Rollback can be performed after delete statement.

TRUNCATE removes all rows from the table. Truncate operation cannot be rolled back.

MYSQL Queries:
1. How will you write an SQL Query to fetch the count of the employee working in project “Q1”?
Here, we would be using comprehensive function calculation() with the SQL where the phrase:

SELECT COUNT(*) FROM Employee Salary WHERE Project = “Q1”;

2. Mention an SQL Query to find the employee id whose salary lies in the range of 16000 and 50000?
Here, we can utilize the ‘Between’ operative with a were part.

SELECT EmpId, Salary

FROM Employee Salary

WHERE Salary BETWEEN 16000 AND 50000;

3. Write an SQL Query to find the maximum, minimum and average marks of the students?
We can use the combined meaning of SQL to bring the max, min and average values:

SELECT Max (Marks),

Min (Marks),

AVG (Marks)

FROM Student Marks;

4. Write an SQL Query to fetch “LAST_NAME” from employee table in upper case?
The necessary query is:

Select upper (LAST_NAME) from Employee;

5. Mention the SQL Query to find the current date and time?
MySQL-

SELECT NOW ();

SQL Server-

SELECT get date ();

Oracle-

SELECT SYSDATE FROM DUAL;
