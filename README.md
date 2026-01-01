# BookBot

BookBot is my first [Boot.dev](https://www.boot.dev) project! It is a simple command-line tool written in Python that analyzes text files (books) to generate interesting statistics about their content.

## Features

- **Word Count Analysis**: Calculates and displays the total number of words in the document.
- **Character Frequency Analysis**: Counts the occurrences of each alphabetic character (case-insensitive).
- **Sorted Reporting**: Displays character counts sorted by frequency (most common to least common).

## Prerequisites

- [Python 3](https://www.python.org/) installed on your system.

## Usage

To use BookBot, run the `main.py` script from your terminal, providing the path to the text file you want to analyze as an argument.

```bash
python3 main.py <path_to_book>
```

### Example

```bash
python3 main.py books/frankenstein.txt
```

## Output Format

The program generates a report in the following format:

```text
============ BOOKBOT ============
Analyzing book found at books/frankenstein.txt...
----------- Word Count ----------
Found 77986 total words
--------- Character Count -------
e: 46043
t: 30365
a: 26743
o: 25225
i: 24613
n: 24367
s: 21155
r: 20818
h: 19725
...
============= END ===============
```
