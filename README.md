# pythonds
Data Structures package for Problem Solving with Algorithms and Data Structures using Python

Some errata and supplyment:

1. In ActiveCode 1 of 4.6: ‘ elif symbol == ")": ’ is better.

2. In 4.21: 
def append(self,item):
        previous = None
        current = self.head
        while current != None:
            previous = current
            current = current.getNext()
        temp = Node(item)
        previous.setNext(temp)
