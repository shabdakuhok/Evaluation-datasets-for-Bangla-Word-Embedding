Our word dictionary named "bangla_words_dictionary.txt" and the processed corpus named "corpus_encoded_files.zip" are available<a href="https://drive.google.com/drive/folders/1yPiCIvJd7u44b5OVKlryNPlDNIazeEa0?usp=sharing"> here. </a>
### How was the corpus processed
The words and punctuation marks in the text files in the corpus have been replaced by the index of the word available in the dictionary and numbers are replaced by the special token `<NUM>`. If the number of occurance of any word is 1 (Meaning a word has occured once in 716,481 articles. So the word is insignificant for our model), we have replaced the word with `<error>` tag.

### How does the processed corpus look like
The processed corpus consists of 716,481 text files each representing an article in our raw corpus. In each text file there are numbers separated by space. Each number represents the index of a word. The word-index relation is available in the "bangla_words_dictionary.txt" file.

