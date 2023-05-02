Download Link: https://assignmentchef.com/product/solved-cmsc204-project-3-circular-linked-lists
<br>
<h2>Project 3</h2>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/892.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/892.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>For this assignment, you will need to implement –

<ul>

 <li>A generic circular singly-linked list class with and iterator</li>

 <li>A generic sorted double singly-linked list class with an iterator that inherits from your generic circular linked class</li>

</ul>

A GUI has been provided for you for this assignment to help you visualize your linked list. Your list classes will also be tested with Junit tests.

<strong>Academic Honesty Policy Reminder</strong> | <strong>Do your own work</strong> – each submitted project will be compared against other submissions from current and previous semesters.

<strong>Specifications</strong>

<strong>BasicDoubleLinkedList</strong>

This generic double single-linked list relies on a head (reference to first element of the list) and tail (reference to the last element of the list).  Both the head and the tail are set to null when the list is empty.

Both point to the same element when there is only one element in the list, and now the element’s “next” reference points to itself. A node structure has only two fields: data and the next references.

The class must only define the following entities –

<ul>

 <li>An inner class Node</li>

 <li>An inner class that implements ListIterator (for the iterator method)</li>

 <li>Head and tail references</li>

 <li>An integer representing the list size.</li>

</ul>




However only the next(), hasNext(), previous() and hasPrevious() methods of the ListIterator are required to be implemented by you.

The rest of the methods can throw the UnsupportedOperationException, such as:

public void remove() throws UnsupportedOperationException{

throw new UnsupportedOperationException();}

All the entities are defined as protected so they can be accessed by the subclass.  Follow the Javadoc that is provided.

<strong>SortedDoubleLinkedList</strong>

A generic sorted double linked list will be constructed using a provided Comparator to determine how the list is to be sorted.  It extends BasicDoubleLinkedList class.

The <strong>addToFront</strong> and the <strong>addToEnd </strong>methods will not be supported and an <strong>add</strong> method will be added that inserts to the doubly-linked list in sorted order dependent on the Comparator.  Follow the Javadoc that is provided.

<strong>Exception Handling</strong>

<ul>

 <li>UnsupportedOperationException – this exception is a Java library exception and will be returned by the addtoFront and addToEnd implementations of the SortedLinkedList class and by the remove method of the iterator.</li>

 <li>NoSuchElementException – this exception is a Java library exception and will be returned by the next function within the iterator class when there are no more elements in the linked list.</li>

</ul>

<strong>GUI</strong>

A GUI driver has been provided to help you visualize your doubly-linked lists.  Here is the minimum that must be in place in order to utilize the GUI effectively.

<ul>

 <li>All methods in your BasicDoubleLinkedList and SortedDoubleLinkedList must be stubbed.</li>

 <li>The <strong>addToFront</strong> or <strong>addToEnd</strong> method of the BasicDoubleLinkedList must be implemented to create a basic doubly-linked list.</li>

 <li>The <strong>add</strong> method of the SortedDoubleLinkedList must be implemented to create a sorted doubly-linked list.</li>

 <li>The <strong>toArrayList</strong> method in both the BasicDoubleLinkedList and SortedDoubleLinkedList, which returns an arraylist of the items in the list from the head of list to the tail of list. This method is used to display the contents of the lists.</li>

</ul>

<strong>Testing</strong>

<ul>

 <li>Create a JUnit Test – BasicDoubleLinkedListTest_STUDENT.</li>

 <li>Create a JUnit Test – SortedDoubleLinkedListTest_STUDENT.</li>

 <li>Run provided “public” test cases</li>

 <li>Anticipate “private test cases to be executed by your instructor</li>

</ul>

<strong>Programming Concepts</strong>

This project utilizes the following concepts:

<ul>

 <li>Exception handling</li>

 <li>Generic Classes</li>

 <li>Doubly Linked List</li>

 <li>Ordered Doubly Linked List</li>

 <li>Iterators</li>

 <li>Comparators</li>

</ul>


