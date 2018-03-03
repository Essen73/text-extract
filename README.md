# text-extract
I am trying to come up with a pyhton based tool to extract text form different types of sources and convert it into a NLP dataset.
In this first version, text from a single pdf file is converted into text using textract and guide from an online article.  The tool is not perfect but a good start.  

Several issues are obvious:
1) entire sentences are showing up as a word; individual words are not being seperated
2) need to isolate title, author, affiliation, figure captions etc fields from the extracted text
