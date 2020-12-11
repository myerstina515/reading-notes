# Reading Notes Class 5

## My thing I learned

## Linked Lists

  - A sequence of nodes that are linked together. There are singly linked and doubly linked. They are a linear data structure, but while going through them, you don't use forEach or for to loop through, the best example would be to use a while() and next(). 
  - The "Head" is the first item in the linked list, and "current" is always the one we're on. Once "current" is set to "head", we create a while loop to check if the "current" one has the value we are looking for. We continue to move "current" to the next link until either the values are matched, or we get to the end of the linked list. 
  - This tutorial is teaching me quite a bit about "addBefore" and "addAfter" that we had as vocabulary yesterday, and here's how it works: if we want to add a node in the middle of the linked list, we add the node to the end initially. Then, we can reassign it to "addAfter" the current node. 
  - It's also helping to explain Big O and the efficiency, with O(1) meaning the second node is being effected, 0(n) is the last node is being effected, and so on. 
  
## What's a linked list Pt. 1

  - Linked lists (and linear data structures in general) are like a game of hopscotch. You have to go through all the links (or nodes) in order to get to the one you want to get to. They are basically the visual equivalent of an array (and now code challenges this week make much more sense!). The difference between arrays and linked lists are how the data is stored. Arrays need all of it's space to be all together, while linked lists can have the data all over the place, as long as there is enough. When we talked about static and dynamic databases today, this relates to it: arrays are like static databases (like SQL), while linked lists are more like dynamic databases (like mongo). THis article takes us through some vocabulary like the previous lesson did, and I will list out the vocabulary:
    1. HEAD: the first node in a linked list
    2. Null: the end of the list is a null value, not actually a node at all, to signify to the program that the list is done. It will return false if it reaches the null. 
    3. Node: the information at the link, as well as instruction to move to the "next" link.
    4. Singly linked lists: have a single track of information that we can go forward.
    5. Doubly linked lists: have a double track of information that can go forward to the next or back to the previous.
    6. Circular linked lists: doesn't end with a null value, it can continue going by referring back to an earlier node in the list. 

## What's a linked list Pt. 2
  - Vocabulary continued: 
    1. Big O: checks for efficiency in the linked list. If code has to process something 10 times before it arrives at the correct locaiton, the code isn't very dry or efficient. O(n) indicates how many steps it has to go through before the process can complete.
    2. Moving nodes around: We are able to mve nodes around efficiently by creating a new node, and then reassigning a number to it. Linked lists are efficient when it comes to moving data around, but searching through it one by one is not. 
    3. Arrays vs Linked lists: they are basically opposites as far as use, but not as far as structure. Arrays and linked lists are both linear by nature, but arrays are fast at searching and slow at moving data, while linked lists are the opposite. Linked lists are ever changing in length and space, while array's are defined and have an endpoint. 
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
