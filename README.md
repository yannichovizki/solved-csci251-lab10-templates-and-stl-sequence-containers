Download Link: https://assignmentchef.com/product/solved-csci251-lab10-templates-and-stl-sequence-containers
<br>
Following completion of this task, students should be able to:

<ul>

 <li>Write C++ programs using class templates and STL Sequence Containers.<strong> </strong></li>

</ul>

<h1>Question 1 (Class Template)</h1>

Create a class template called ObjectContainer that holds an object and the number of data elements in the object.  For example, if an Employee class has two data elements, an ID number and a salary, then the class template holds the number 2 and an Employee object; if a Student class contains 12 data elements, then the class template holds 12 and a Student object.

Write an overloaded extraction (&gt;&gt;) operator for the ObjectContainer class template that displays a message on the screen – “You will be ask to enter X items” – where X is the number of data elements and then continue to read the details for the object it is holding. To do this, the class which object is kept in the class template must also overload the extraction operator (&gt;&gt;). Implement also the insertion operator (&lt;&lt;) for all the classes involved.

Write a main() function that tests your template class with objects from two different classes of your choice.

<h1>Question 2 (STL – Sequence Containers)</h1>

A palindrome is a sequence of characters, numbers or words that have the property of reading the same in either direction (backwards or forwards). In a palindrome white space and punctuation have no significance

(they are typically ignored).

Examples of palindromes are shown below:

<strong>121  </strong>– A numeric sequence

<strong>GACTTCAG </strong>– A DNA Sequence

<strong>Sator Arepo tenet opera rotas </strong>– A latin phrase for: <em>The farmer by his labour keeps the wheels to the plough.</em>

As you can see in the last example, white space and capitalisations are ignored. You are to write a program that takes in a sequence and works out if it is/isn’t a palindrome.

Write a C++ program that reads a string/sequence from standard input until eof. The string/sequence, including all white space, punctuation and newline characters should be read in character-by-character and stored into a vector. The vector should hold objects of type char. When the sequence is finished being read in, create two iterators. One iterator points to the beginning and the other the end of the vector.

By using these iterators you can work out if the sequence is the same in both forward and reverse directions.

Remember that you should ignore case, punctuation and white space characters.  If the sequence is a palindrome, you should print it out in both forward and reverse directions and indicate it is a palindrome. Otherwise display an error message.


