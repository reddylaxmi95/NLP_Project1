# NLP_Project1
 The Project is to construct a document-term matrix, which is a 2-dimensional matrix that describes the frequency of terms (i.e., words) that occur in each document in a collection. In a document-term matrix, rows correspond to documents in the collection and columns correspond to terms. The value in a given cell (i, j) represents the number of times the j-th term occurs in the i-th document.
 The text file 'urls.txt' contains a list of urls for the webpages to be parsed. Each line in the text file corresponds to a specific URL which will be passed to the Parse_URL funcion to retrieve the data from the URL. the content of each URL is a single document.
 
 The function document-term matrix takes two parameters; the first parameter is the name of the text file containing URLs and the second is the name of the text file containing stopwords.The output of the funtion is  two DataFrame, df1 and df2 which are the document-term count matrix and the second is the term frequency value matrix

