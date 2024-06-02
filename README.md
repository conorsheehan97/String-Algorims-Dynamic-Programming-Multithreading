# String Searching Algorithms and Dynamic Programming Solutions
## Overview
This project explores various string searching algorithms including the Naive Algorithm, Boyer Moore algorithm, and the Knuth-Morris-Pratt (KMP) algorithm. Additionally, it implements Dynamic Programming solutions to tackle the Knapsack Problem and the Longest Common Subsequence problem. Furthermore, multithreading techniques are applied for efficient matrix multiplication.

## String Searching Algorithms
 - Naive Algorithm: Basic pattern searching method that slides the pattern one by one and checks for a match.
 - Boyer Moore Algorithm: Efficient algorithm that preprocesses the pattern and skips characters in the text based on mismatch cases.
 - Knuth-Morris-Pratt (KMP) Algorithm: Algorithm that preprocesses the pattern to create a partial match table, allowing it to skip unnecessary comparisons.

### Data Collection
 - Source: HBO website for the Chernobyl Miniseries transcripts.
 - Process: Scraped PDFs converted into text bodies for each episode.
### Keyword Analysis
 - Keywords: Analyzed counts of keywords like "Comrade," "Graphite," and "Roentgen" per episode using all three string searching algorithms.
 - Comparison: Runtime analysis of each algorithm for keyword counts per episode.

## Dynamic Programming
### Knapsack Problem
 - Approaches: Implemented both Brute Force and Dynamic Programming approaches.
 - Benefits: Dynamic Programming optimizes by storing solutions to overlapping subproblems, improving runtime efficiency.
### Longest Common Subsequence
 - Method: Dynamic Programming used to find the longest subsequence common to all sequences in a set of sequences.

## Multithreading Matrix Multiplication
 - Objective: Efficiently multiply two matrices using Python's threading package.
 - Process: Divided matrix rows among threads for parallel computation, enhancing performance.

## Packages Used
 - matplotlib: For plotting runtime comparisons.
 - requests, BeautifulSoup, pdfplumber: For web scraping and PDF parsing.
 - pandas, numpy: For data manipulation and algorithm implementation.
 - time: For runtime analysis.
 - threading: For multithreaded matrix multiplication.

## Conclusion
This project provides a comprehensive exploration of string searching algorithms, Dynamic Programming solutions, and multithreading techniques. By analyzing Chernobyl Miniseries transcripts and implementing various algorithms, it demonstrates practical applications in text analysis, optimization problems, and parallel computing.

Contributions and feedback are welcome to enhance the functionality and expand the capabilities of this project.
