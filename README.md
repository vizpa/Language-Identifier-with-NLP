# Language-Identifier
Language Identifier using NLP

Main Source: WiLI-2018
The Wikipedia language identification benchmark dataset (found in Kaggle), contains 235000 paragraphs of 235 languages. 
Each language in this dataset contains 1000 paragraphs. 
https://www.kaggle.com/sharansmenon/wili-2018

This Language Identifier works with only 25 languages selected from the source.

Tokenizing Asian text:
Languages like Chinese and Japanese contains continuous stream of characters with no explicit separators, one way to tokenize and use segmentation in these texts is to use Half-overlapping bi n-grams. In order to preserve some words, it is necessary to overlap symbols to create constructs that will help match the right bi n-grams. <br>
This estimation shows to be highly effective. 
https://www.youtube.com/watch?v=HYwKGZIvvb4

Tools:
Python - Jupyter Notebook
