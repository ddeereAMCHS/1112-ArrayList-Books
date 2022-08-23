# ArrayList Books

## Due: DoW MM/DD at 11:59 PM

- Create a Book class
- The class should have the following data members:
  - Title
  - Author
  - Number of pages
  - Rating
- Write a default constructor
- Write a parameterized constructor that sets all four data members
- Write getter and setter methods for each data member
- Write a method called isPopular that returns true if the rating is greater than 4.0
- Write a method called isLengthy that returns true if the number of pages is greater than 300
- Write a method called isShort that returns true if the number of pages is less than 100
- Write a toString method that returns the title and the author with the word "by" in between them
  - Ex. The Cat in the Hat by Dr. Seuss
- - - - - - - - - - - -
- Create a program called `BookTester.java`
- Prompt the user for a filename
- Create an ArrayList that will hold Book objects
- For each line in the file:
  - Split the line on semicolons
  - Trim the split values
  - Make a Book object from the values
  - Add the Book object to the ArrayList
- Print the list
- Print all books that are popular and lengthy (include a header, see example output)
- Print all books that are short (include a header, see example output)

***Example Input:***\
books.txt\
***Example Output:***\
[The Cat in the Hat by Dr. Seuss, The Lightning Thief by Rick Riordan, Fahrenheit 451 by Ray Bradbury, The Scarlet Letter by Nathaniel Hawthorne, Heir to the Empire by Timothy Zahn, If You Give a Mouse a Cookie by Laura Numeroff, Twilight by Stephanie Meyer]\
\
Popular and lengthy books:\
The Lightning Thief by Rick Riordan\
Heir to the Empire by Timothy Zahn\
\
Short books:\
The Cat in the Hat by Dr. Seuss\
If You Give a Mouse a Cookie by Laura Numeroff
