# C++ Search Engine using List, Map, and Trie

This is a C++ search engine project that uses List, Map, and Trie data structures to search for specific keywords within a given text file. This project is designed to demonstrate how to use these data structures to efficiently search for keywords in a large data set.

## Getting Started

To get started with this project, you will need to download the source code and compile it on your local machine. Once compiled, you can then run the program and provide it with a text file to search.You have use the make file to run the code in the terminal.

## Prerequisites

To run this program, you will need to have a C++ compiler installed on your system. We recommend using the g++ compiler for Linux systems and Microsoft Visual Studio for Windows systems.

### Compiling the Program

1. Download the source code from the Github repository.


2. Open a terminal (or command prompt) and navigate to the directory where you downloaded the source code.


3. Compile the program using the following command:
      
        g++ -std=c++11 searchengine.cpp -o search_engine

This will create an executable file called search_engine in the same directory.     

## Running the Program

1. Open a terminal (or command prompt) and navigate to the directory where you compiled the program.

2. Run the program by providing the name of the text file you want to search as a command-line argument:

        ./search input.txt     
   Replace input.txt with the name of the file you want to search.


3. Once the program is running, you will be prompted to enter a keyword to search for within the text file. Enter the keyword and press Enter.


4. The program will then search the text file for the keyword and display the results.

## How it Works

This search engine uses a Trie data structure to efficiently search for keywords within a given text file. A Trie is a tree-like data structure where each node represents a character in a string. By storing the text file in a Trie, we can quickly search for any given keyword by traversing the Trie.


The program also uses List and Map data structures to store and sort the search results. The List is used to store the search results in the order they were found in the text file, while the Map is used to store the search results in alphabetical order.


The code is organized into several classes, including TrieNode, Trie, SearchResult, and SearchEngine. The TrieNode class represents a node in the Trie data structure, while the Trie class is used to build and search the Trie. The SearchResult class represents a single search result, and the SearchEngine class is used to manage the search process.

## Conclusion

This C++ search engine project is a great example of how to use List, Map, and Trie data structures to efficiently search for keywords within a large text file. With some modifications, this project can be expanded to search for keywords within multiple text files, or even entire directories of text files. The code is well-organized and easy to modify, making it a great starting point for more complex projects.
