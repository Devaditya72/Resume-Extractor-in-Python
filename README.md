# resume-parser-in-python
A parser to extract information from resumes in PDF and DOCX formats written in Python

##Dependencies
The parser requires two Python modules for it to work as intended,

1. [PyPdf](https://pypi.python.org/pypi/pyPdf/1.13)
2. [python-docx](https://python-docx.readthedocs.io/en/latest/)


The module used for tokenizing and stop word removal are:

1. word_tokenize from nltk.tokenize  #can be replaced with the split() which is built-in
2. stopwords from nltk.corpus 

To get both you'll to install the Python NLTK module.

The script is written in Python 3.7.6
