### DATA STRUCTURES
- STACKS
  - Follows LIFO
  - Additions are made to the top
  - Push, Pop, Display
  - STATIC Stack
    - Can only be used for a preset number of nodes.
  - DYNAMIC Stack
    - Makes use of linked implementation to keep track of next memory block.
    
- QUEUES
  - Follows FIFO
  - *Additions* are made to the *rear*, **deletions** are from the **front**
  - Enqueue, Dequeue, Display
  - STATIC Stack
    - Can only be used for a preset number of nodes.
    - Circular Queues are more practical for fixed number of nodes.
  - DYNAMIC Stack
    - Makes use of linked implementation to keep track of next memory block.
    
- DOUBLY LINKED LISTS
  - Keeps track of the element which is before and after it as prev and next
  - Better than Singly linked lists as it allows access to the list from both directions
  - Deletion and insertion of an arbitrary node is easier
  - Inertion can be of four types
    - At Front
    - At Rear
    - After a specified node
    - Before a specified nodde
  - Display can be of two types
    - Display from front
    - Display from rear

- HASH TABLE
  - a.k.a Hash Map as it maps data to indexes
  - Makes use of associative arrays to map keys to values
  - Links a unique index for each slot in the array (which acts similar to a primary key) using a hash funtion

- BINARY TREES
  - Is an heirarchical data structure
  - Allowed to have only two child nodes, left and right child
  - Each child nood can either be a leaf(i.e. no successor) or a root to further nodes
  - Is the preffered tree structure where searching for data items is more frequent
  - Can be conviniently used for representing fixed mathematical equations
  
- RED & BLACK TREES
  - Is an hierarchical data structure
  - Every node is either red or black; the root of the tree is always black
  - There cannot be two adjacent red nodes (i.e children of a red node must be black)
  - Is a preffered tree structure involving multiple insertions and deletions
  
