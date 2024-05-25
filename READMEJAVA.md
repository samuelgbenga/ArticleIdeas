# Java Articles Idea

## Made a discovery

#############
### Interface Discovery
- once you made a class to implement an interface,
by default all method in the implementing class
becomes inaccessible to other class if not
explicitly defined in the interface class
as "public"
- I don't know if it same for abstract 
classes which partial abstraction\
#############

## Java PriorityQueue
- PriorityQueue is a part of Java's collections framework.
- PriorityQueue does not prioritize literaly without the help of poll.
- that means the effect of PriorityQueue only takes effect when you use .poll to pull element from the queue. else the arrangement of the element is not guranted even with the implementation of Comparator, if you are to traverse throught the PriorityQueue literaly or using an Iterator interface. 
