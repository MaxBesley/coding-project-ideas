# **Coding Project Ideas**

## **About**

This is a simple repository where I store descriptions of programming projects that I would like to implement in the future. This exists purely as a form of record keeping for myself and probably won't be relevant to other people.

## **List of Ideas**

- A program which takes an image as input, applies a hash function to every pixel of the image, and then returns the hashed image as output. The code may include many different hash functions (for the purpose of experimentation). Possibly the name of the hash function to be used could be passed as the second input parameter to the program (this would be interesting to try and implement). The hash functions would have to take an RGB value (rValue, gValue, bValue) as input and return a new (seemingly random) RGB value as output. Maybe written in Python.

- A program which takes an executable file (i.e a file produced by a C compiler) as a command line argument and converts the executable to a series of bits. Printing to standard output, with *PER_LINE* bits on each line of output. Written in C.

- Maybe implement the game of chess in Java. Where the players use the traditional notation of A5, D2, F6 etc. There can be some kind of GUI window that opens up when the program is run, and the two players can make moves in turns. Users can make moves by typing in notation such as _E2 -> E4_ (meaning “move the piece at E2 to E4”) or _G5 -> F4_. Of course, the program must check that these moves are valid. There are many ways to design this game and it won’t require a small amount of code. As an extension, create an AI to play against that picks a random move each turn.

- Implement Markov chains in an OOP language such as Java.

- Finish the linked list implementation in C that I started. Make it as general and polymorphic as possible. Maybe even make it a doubly linked list, for the sake of making it challenging.

- Finish the BST implementation in C that exists somewhere on my laptop.

- Implement a priority queue in C. Include all the basic operations/functions including a `trim_to_size()` operation. Write a `main()` function for testing. Once that is done the project could be extended by using the PQ to implement heap-sort.

- Implement a caesar cipher. At the moment C seems like the most appropriate language to use. The program should take a text file (the plaintext) as input (using the command-line) and then output the cipher text (writing it to either standard output or a new text file). The amount to shift by should be given as a command-line argument. An example execution would be: **./casar_cipher plantext.txt 22**

- Implement multiple string search algorithms in C. After reading the relevant chapter in [Introduction to Algorithms](https://mitpress.mit.edu/books/introduction-algorithms-fourth-edition "Textbook link").

- Implement some graph algorithms in whatever language seems most appropriate (would Haskell work or what about OOP in Python?). The graphs should be represented using an adjacency matrix. The adjacency matrix could be hardcoded into the program (i.e by initialising a 2D array) or could be read from a CSV file.

- Attempt to write the shortest possible [Quine program](https://en.wikipedia.org/wiki/Quine_%28computing%29 "Link to wiki page") in Haskell.

***
