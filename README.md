# Heap-optimization
The structure of a heap can be represented as a tree in which each element has its own ordered index, its (two) "children" and its (one) "parent".  
![](Images/HeapTree.jpg)  
If we know the index of a node, we can also find out the indexes of its parent and children.  
>Index rule:
>1) parent: **(n - 1) / 2**
>2) child left: **2n + 1**
>3) child right: **2n + 2**


## Add element to the heap

***
# Thanks for [Sebastian Lague](https://www.youtube.com/@SebastianLague)