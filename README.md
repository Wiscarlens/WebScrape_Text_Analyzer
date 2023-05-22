Web Scrape Text Analyzer
In this plan, we outline the steps to retrieve text from a URL, preprocess it, and perform a word frequency analysis. 
The objective is to analyze the frequency of each word in the text and present the results in descending order.

Firstly, the input is accepted from a URL. The URL is opened, and its contents are read to obtain the text for analysis. 
To prepare the text for processing, several preprocessing steps are applied. The text is converted to lowercase to treat 
all words case-insensitively. Punctuation marks and special characters are removed to isolate the individual words. 
The preprocessed text is then split into individual words, forming a list for further analysis.

An empty dictionary is initialized to store the word frequencies. The next step involves iterating over each word in the 
preprocessed text. For each word encountered, the algorithm checks if it already exists in the dictionary. If it does, 
the frequency count for that word is incremented. If the word is not present, it is added to the dictionary with an initial 
frequency count of 1.

Once the word frequencies have been calculated, the dictionary is sorted based on the values in descending order. 
This sorting process ensures that the words with the highest frequencies appear at the top of the list. Finally, the word 
frequencies are printed. The algorithm iterates over the sorted dictionary and, for each key-value pair, prints the word 
and its corresponding frequency count.
