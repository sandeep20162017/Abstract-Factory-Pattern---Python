# Abstract-Factory-Pattern--Python
Abstract Factory Pattern - Python - Sandeep Kanao

In this example, Document objects (Word, PDF, HTML etc) interact with Parse objects (WordParser1, WordParser2, PDFParse, HTML parser etc.), but there are different types of
Documents and Parsing depending on document types and parsing technics. 

One document type can have more than one document type parser (exampe wordtype document can have wordtypedoc1 parser, wordtypedoc2 parser)

Each of the factory methods creates a different kind of object. 

The idea is that at the point of 
creation of the factory object, you decide how all the objects created by that factory will be used. 
