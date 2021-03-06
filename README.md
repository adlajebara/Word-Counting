# Word-Counting
I wrote this code while taking a summer course at Chalmers university.

This was the first lab assignment which focuses on a technique which can be found in many algorithms that allow machines to understand human language. The code includes tokenization, how to split a running text into a sequence of words (tokens) and word counting, aggregate statistics for the frequencies of different words.


## How to run it
The program can count words from a text file or fetch data directly from the web. The data to be analysed needs to be specified in the third argument.

How to run it:
```bash
python3 topmost.py eng_stopwords.txt <text file to analyze> n
```

Example:
```bash
python3 topmost.py eng_stopwords.txt examples/article1.txt 20
```

The last parameter n is the number of words to be printed.

## Files
* The examples folder contains examples of text files to be analysed
* eng_stopwords.txt contains a list of English stop words
* topmost.py contains the main function
* wordfrequency.py contains the tokenize, word count and print functions
