# String-Algorims-Dynamic-Programming-Multithreading
In this body of work, we implement String Searching algorithms including the Naive Algorithm, the Boyer Moore algorithm, and the KMP algorithm. We then implement Dynamic Programming solutions to solve the Knapsack Problem, and the Longest Common Subsequence. We finally implement some multithreading matrix multiplication for a 100x100 matrix.

To expand on this a smidgeon. We begin with String Searching algorithms. These algorithms that we're going to look at are used to search a large body of text for a pattern, or an item of subtext. To obtain data for this, we first scrape the HBO website, for the publically available Chernobyl Miniseries transcript per episode. We then convert the obtained PDF's into a list of 5 (per episode) bodies of text. We then check the count per episode for certain keywords (e.g. Comrade, Graphite, Roentgen) using the Naive Algoritm, Boyer Moore, and the KMP algorithm. We use the calculation runtime of each algorithm as our comparison. 

We also solve the Knapsack problem, using a Brute Force method, then by being more clever about things, and usuing a Dynamic approach. Dynamic Programming essentially involves breaking a big problem, down into smaller problems and solving those problems first. The overall problem often contains multiple occurences of the same subproblem, hence, by having already solved the sub problem, we can use this result and not have to calculate it, saving on runtime. This sub-result, is either saved through tabulation, or memoization. We use Dlynamic Programming to solve both the KnapSack problem, and the Longest Common Subsequence problem. 

We finally perform some multithreading to multiply together two matrices using the threading package. During matrix multiplication, each element in the resultant matrix can be calculated independant of one another. Therefore, using the threading package, we assign a certain amount of rows (0.25 in our case) to a thread, calculating each segment simultaneously, and then rejoining our threads. 

Algorithms used: Naive Algorithm, Boyer Moore Algorithm, KMP, Dyanmic Programming to solve Knapsack & Longest Common Subsequence,

Packages used: matplotlib, requests,BeautifulSoup, pdfplumber, pandas, numpy, time, threading
