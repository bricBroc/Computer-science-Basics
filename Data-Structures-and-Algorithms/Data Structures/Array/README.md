# Arrays
## ELIM5
- Think of an array like a shelf with compartments.
- Each compartment can hold one item. Now, imagine you have a bunch of books, and you want to organize them on this shelf.
- You decide that each compartment will hold one book, and you label each compartment with a number.
- So, if you have ten books, you'll put each book in its labeled compartment, from 1 to 10. If you want to find a specific book, you just look at its compartment number, and you'll know exactly where it is.

## The Interview version
- Arrays are fundamental data structures in computer science
- They play a crucial role in organizing and managing collections of elements. 
- At its core, an array is a contiguous collection of items stored at contiguous memory locations, each identified by an index or key. This arrangement enables efficient access to elements based on their position within the array.

## Applications
- managing student records in a school database ( organize student data like name, age, grade, contact...) 
- financial modeling and analysis ( store historical market data)

## Inconveniences
- Fixed Size: you need to know the maximum number of elements beforehand. If you exceed this size, you may encounter errors or need to reallocate memory

- Contiguous Memory: all elements must be stored in adjacent memory locations. Inserting or deleting elements in the middle of an array can be inefficient, requiring shifting of elements.

- Static Structure: array size and dimensions cannot be changed dynamically during runtime.

- Inefficient Insertions and Deletions: In dynamic arrays, resizing operations may be required, leading to additional overhead.

- Wastage of Memory: especially if the allocated size is larger than necessary.

- No Built-in Functions for Operations: Developers may need to implement these functionalities manually, leading to additional code complexity and potential errors.

- Homogeneous Data Type: Arrays typically store elements of the same data type. Managing heterogeneous data may require additional data structures or complex handling.

## Implementation
- <a href=""> C </a>
- <a href="google.com" >C++</a>
- <a href="">Python</a>
- <a href="">Java</a>
