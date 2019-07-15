### For 7/14/19
IMPORTANT: Read both files [HowToUseGithub](https://github.com/rhansolo/GettingStarted/blob/master/HowToUseGithub.md) and [TerminalCommands](https://github.com/rhansolo/GettingStarted/blob/master/TerminalCommands.md)
You should start to memorize those commands and I won't be stopping in class to help you later on.     
  
WHERE TO WRITE THE HOMEWORK:
- Create a folder inside the homework folder and label it with the day this homework is assigned. Inside that folder, place all your homework files and name them appropriately. 
- I will be checking on the Friday before we have class so make sure its uploaded online by that time.
- **If you have any questions relating to the homework or classword, post on the QAF( Q and A Forum) to let me know and other students. You guys are encouraged to help each other by answering each other's questions without me having to answer them for you**  
  
Homework:
- Finish the Stack Question given in class (Use the built-in Java class Stack)
- Create a LinkedList Object Class.
Lets call each entry of the LinkedList a Node. The **Node object** will have the following properties 

Fields:
  - Node next,prev
  - Integer data

Methods:
- Node next()
- Node prev()
- void setNext(Node other)
- void setPrev(Node other)
- Integer getData()
- Integer setData(Integer i)
- String toString()

The **MyLinkedList Object** Class will make use of the Node Class. Here are its properties

Fields:
   - Node start
   - Node end
   - int length   

Constructor:
   - MyLinkedList() - make an empty list.

Public Methods:  
   - boolean add(Integer value)
   - int size()    
   - String toString()  
   - Integer get(int index)  
   - Integer set(int index,Integer value)
   - boolean contains(Integer value)
   - int indexOf(Integer value)
   - void add(int index,Integer value) 
   - Integer remove(int index) 
   - boolean remove(Integer value) // removing a specific node
