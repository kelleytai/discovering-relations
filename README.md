# discovering-relations
Hearst's algorithm 

With NLTK and using Hearst’s lexicosyntactic patterns, I built and evaluated a system for finding suggested hyperonym / hyponym relations between words in a corpus of text. I used NLTK’s regular-expression chunk parser to get the data into a form ready for pattern-matching.

A corpus of about 2.6 million sentences (60 million words) from the 2004 New York Times tagged with parts of speech was used on my alogirthm. The NYT corpus has already been part-of-speech tagged but not partially parsed or chunked.   

This repository contains my evaluation of the output of my algorithm. It contains pairs of hyponym. The first word in the pair is the smaller subset of the second word. 

Please e-mail me if you would like to see the Hearst.py code or the corpus I used. 
