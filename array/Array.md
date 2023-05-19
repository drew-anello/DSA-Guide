# Array's

This is probbably a Data structure everyone is familiar with. You may think that ```const a = []``` is an array but it's not... well what is it? 

### <u>What is an Array?</u>

An array is a contiguious (un-breaking) memory space in which contains a certain amount of bytes. Everything about a computer is just numbers. 



*note about bytes and bits* in this case were looking at chunk of memory which is 4 bytes

- a byte is a unit of digital information that typically consists of 8 bits. Each bit can have a value of either 0 or 1.
- inorder to caluclate the bits we would do number of bytes (in this case 4) times number of bits (8).


There are low-level languages and high-level languages. When using a high-level language like JavaScript or Python, you'll find that it is relatively easy to understand. In other words, a high-level language is closer to natural languages like English. For example, in high-level languages, we don't have to deal directly with machine code or worry about low-level hardware details. We can take many things for granted, such as not having to manually manage the CPU and having built-in data structures. However, it's important to note that high-level languages actually perform a lot of operations behind the scenes. What you write in JavaScript or Python is ultimately compiled into a sequence of 0's and 1's, which is the machine code understood by the hardware.

<br>

<br>

**Examples of some Low and high level languages**

| Low Level Languages | High Level Languages |
| ------------------------- | ------------------------ |
| Machine Code              | JavaScript / TypeScript |
| Assembly                  | Python                   |
| c             | Java                     |
|          c++                  | PHP                      |


<br> 

**Insertion at a specific index** 

- when insert something it doesnt magically insert something it overwrites it

**Delete at specific index** 

- deltion is similar but a bit differnt, this is where null comes in
- you need to tell yourself when you delete this memeory
- null being the 0th value. 
  

## **<u>Array in Summary</u>**

- They are fixed sized, continiguous memory chunks
- that means you cannot grow it 
- there is no insertAt or push or pop. Doesnt mean you can't write those though.

 <br>


  ## [Click Here For the Next Lesson](../search/Search.md)


 