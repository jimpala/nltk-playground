nltk-playground
===============

Repository for playing around with code from the O'Reilly Python NLP book.

##Setup
When using NLTK, we'll be downloading corpora using the `download()` function. Set the `download_dir` kwarg to the 'corpora' directory. When the download screen prompt comes up, pick 'book' from the list of corpora.

To get NLTK to look here for corpora, we'll need to add in our executable code:

`nltk.data.path.append('path/to/copora')`