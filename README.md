# thai_tree_parser
A syntax tree parser for thai

This will be in the form of a web app or a python package that can be used to take in a sentence in Thai and build all possible syntax trees for a user to see. This will require two principle steps: part of speech tagging and tree parsing. The first task is not as interesting to us as the second, though it will be a critical stage. We plan to use this python library to do the part of speech tagging for Thai. Then we will use NLTK to build a Thai parser that operates on the principles of XBar theory. Using UTF-8 encoding will allow us to handle Thai orthography. A user will enter a Thai sentence and all parse trees possible under our rules will appear on the screen for them to select from. This will be coded in Python (and maybe some Latex) for easy accessibility.
