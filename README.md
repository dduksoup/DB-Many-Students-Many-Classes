# DB-Many-Students-Many-Classes

The original code for this program was provided 
by University of Michigan's online course
"Using Databases with Python" on Coursera.

The code is then modified to read JSON data provided
by the course instructor, store relevant data into 
three separate SQL tables in order to portray
a many-to-many data model.

More specifically, the program:
- Parses the JSON data
- Looks for several types of information related to student and class
- Sets up SQL tables
- Loops through each student/class tuple data in JSON
- Stores data accordingly in the junction table

At the end, you can run an SQL query on the junction table
that helps you look at what students are in a class or
what classes are taken by a student, vice versa.