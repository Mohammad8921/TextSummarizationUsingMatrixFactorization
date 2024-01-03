# Text Summarization Using Matrix Factorization
## Data preprocessing
The preface section of the Introduction to Algorithms (3rd edition) book written by Cormen et. al., which is known as CLRS, is considered as the input text. This section of the book is approximately 7 pages long and contains 156 sentences. All punctuations and stop words are removed from the text and the words are stemmed. Finally, the TD-IDF matrix, $A$ is created for the text.
## Singular Value Decomposition (SVD)
This method can be called the first rank approximate of the matrix. applying SVD on $A$ results in $𝐴=𝑈Σ𝑉^𝑇$. The first column of U and V indicate the most important words and sentences respectively. the first three sentences in the ranking of importance are:
1. edu/algorithms/, links to solutions for a few of the problems and exercises.
2. edu/algorithms/, links to solutions for some of the problems and exercises so that you can check your work.
3. edu/algorithms/, links to these solutions.

## Key sentences extraction using $k$-th rank approximation
This is an iterative algorithm that benefits Non-negative Matrix Factorization (NMF). As we saw above, the sentences obtained from the previous method are similar to each other and convey the same concept. To fix this issue we should use $k$-th rank approximate of the matrix instead which is done by NMF with $k$-components. It returns $k$ key sentences in $k$ steps. By setting $k=10$, the first three sentences in order of importance are:
1. This is a large book, and your class will probably cover only a portion of its material.
2. A quick look at the table of contents shows that most of the second-edition chapters and sections appear in the third edition.
3. Departing from our practice in previous editions of this book, we have made publicly available solutions to some, but by no means all, of the problems and exercises.

