# NLP Syntactic Transfer Translator

A program that translates sentences from Italian to English. 

The nltk library in Python was used to generate the constituent tree, given the grammar defined in an initial phase. 

The constituent tree produced in the parsing phase is processed later by a program implemented in Java. 

For the generation of the English sentences, the Simple-NLG library was used. 

Thanks to this library it was possible to define the sentence plan starting from the syntactic tree: in this way the morphological realizations of the words due also to the syntax were automatically managed by the library.
