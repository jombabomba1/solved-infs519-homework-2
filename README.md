Download Link: https://assignmentchef.com/product/solved-infs519-homework-2
<br>
In this program you will replace the linked list from Program 1 with a binary search tree as the basis for your address book. You will also save your address book in a text file.

Your program will appear the same as Program 1 to the user <em>except </em>that it will first ask the user”Do you want to open a file? (y/n).” If the user answers “y” the program will ask for a file name, open and read the input file. Each pair of lines from the input file will be made an entry in the address book: a name line and an address line. If the user answers “n” the program will not open a file. In either case the program will continue as did Program 1.

A new operation “save” will be added to the menu. When the user selects “save” the program will ask the user for the name of a file in which to write the address book, open the file and write the entire address book to the file. This operation will be very similar to the “displayAll()” operation.

<strong>Internals</strong>

Again, you will write (among other classes) a class <strong>Table </strong>which will store entries comprised of (key/value) pairs of Strings. This class will have the same public methods as did Program 1 with the addition of

a <strong>public void save(</strong>) method and it will have none of the “mark” classes.

Table will now be implemented as a binary search tree. Each node will have two String fields (for the name and address). insert, lookUp, delete, and update will use binary search tree operations (which you will write). You will use traversals to implement “displayAll()” and “save() “. For ” displayAll ()” use an in-order traversal but for “save” use either a pre- or post-order traversal.

<strong>To turn in</strong>

As before, you will turn in a well-commented source listing via Blackboard.