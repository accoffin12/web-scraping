# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt

# Requirements & Installation:
In order to exicute the code in this repository the following is required:
    * Python(version3.x) 
    * Libraries: requests, pickle, beautifulSoup, spaCy, Collections, string, matplotlib

To use this project the root must be at least Python 3.8, and it is recomended that a virtual enviroment is created prior to running any install commands for missing libraries.
When installing libraries be sure these are all present:
    1. beautifulsoup4 
    2. html5lib
    3. spaCy
    4. spaCytextblob

# Methods:
1. Extract Articl XML
2. Process Text using Parsers and NLP
3. Data Visualization in the form of histograms

# Results:
This project is a demonstration of how the use of filters when utilizing tokenizers and lemmas extracted from an article can vary based on call. There are several variations of filter applied, one demonstrating the removal of stop_words and the other creating both lemma and token filters using "NOUN" as a parameter. Due to the early application of a modified Stop_Word filter the results between the two are visually the same. However, the words which are classified as most common are radically different. This is explored at the end of the porject. 

## Conclusion: 
The Laser Headlights Analysis project demonstrates how to extract, process, analyze and re-evaluate text data from a web article. With the use of various libraries it is possible to find valuable insight into the content of the article as well as the value in Natural Language Processes. 