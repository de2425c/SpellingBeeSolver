# SpellingBeeSolver
New York Times Spelling Bee Solver that calculates all possible words from a text file given a seven letter user input
- @Author David Eyal
- @Version 1.0 December 31 2023

# GUI

Built with Swing GUI

Example Solution

![Screenshot 2023-12-31 132932](https://github.com/de2425c/SpellingBeeSolver/assets/154690407/a41a75f5-b8a4-4466-b340-a461f89c8a03)
![Screenshot 2023-12-31 132956](https://github.com/de2425c/SpellingBeeSolver/assets/154690407/a33309e0-16b1-4f97-803a-303571f12171)

# Techniques Used

- Java HashMap for storing Dictionary Words with Key Value Pair (Key = sorted lowercase anagram, Value = List of words)
- Java BufferedReader/FileReader for scanning a dictionary.txt file
- Adapted Combinatoric Algorithm for storing all combinations of anagrams of 7 letters up to length 11 with repitition
- Set logic to remove duplicates
- Insertion Sort algorithm to sort output and sort a String through char array (for key-value mapping)

# Runtimes

- Runs in under 1s for seven letter inputs

# Contact

de2425@columbia.edu

