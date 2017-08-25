# discovering-relations
Hearst's algorithm 

With NLTK and using Hearst’s lexicosyntactic patterns, I built and evaluated a system for finding suggested hyperonym / hyponym relations between words in a corpus of text. I used NLTK’s regular-expression chunk parser to get the data into a form ready for pattern-matching.

This repository contains:
1. NLTK Corpus: A corpus of about 2.6 million sentences (60 million words) from the 2004 New York Times tagged with parts of speech is available in this repository. The Python object nyt mini is a small development corpus that contains 100,000 sentences selected from nyt big. The output of this algorithm uses nyt_big. The NYT corpus has already been part-of-speech tagged but not partially parsed or chunked. 
2. Hearst Evaluation: My evaluation provides an easier way to view the output of my algorithm. It contains pairs of hyponym. The first word in the pair is the smaller subset of the second word. 
