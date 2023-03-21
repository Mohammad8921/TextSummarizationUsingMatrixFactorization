# Text Summarization Using Matrix Factorization
## Data preprocessing
The preface section of Introduction to Algorithms (3rd edition), which is known as CLRS, was considered as the input text. This section of the book is approximately 7 pages long and contains 156 sentences. All ounctuations and stop words were removed from the text and the words were stemmed. TD-IDF matrix were created for the text.
## Singular Value Dicomposition (SVD)
This method can be called first rank approximate of the matrix. Using SVD for TD-IDF matrix, $A$ gives us $𝐴=𝑈Σ𝑉^𝑇$. The first column of U and V 
indicate the most importance words and sentences respectively. First three sentences are:
*.edu/algorithms/, links to solutions for a few of the problems and exercises.
*.edu/algorithms/, links to solutions for some of the problems and exercises so that you can check your work.
*.edu/algorithms/, links to these solutions.
