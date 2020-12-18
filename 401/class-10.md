# Stacks and Queues:

## Stacks
  - Common terms include *push, pop, top, peek, and isEmpty*
  - A stack is a structure consisting of nodes, just like a linked list, each one can see the next one, but none can see behind them.
  - There are two different ways for stacks to be structured: FILO or LIFO (translates to first in last out, or last in first out, respectively).
  - When you push a node onto a stack, it goes on the top, it becomes the "first" node, and its "next" becomes the previous first one. When you "pop" a node, you take the one off the top.
  - You can also "peek" at the top node after checking to see if the stack "isEmpty" or not.
## Queues
  - Queues are similar, but instead of having a top and bottom, it has a front and rear. Instead of terms like FILO or LIFO, queues abide by FIFO or LILO (which, as you may have guessed stand for first in first out, and last in last out). 
  - Common terms include *enqueue, dequeue, front, rear, peak, and isEmpty*
  - When you add, or *enqueue* a node, it automatically adds to the *rear* of the queue. It's next is null, and it becomes the next to the previous rear itself.
  - When you *dequeue*, you are removing a node from the front of the queue, and you reassign the nexxt one to be the "front" node.
  - When you conduct a *peak* typically, you'll check to see if the queue *isEmpty* first, and if it's not you can peek at the front node of the queue.
