# text-extract
I am trying to come up with a pyhton based tool to extract text form different types of sources and convert it into a NLP dataset.
In this first version, text from a single pdf file is converted into text using textract and guide from an online article.  The tool is not perfect but a good start.[Source: https://medium.com/@rqaiserr/how-to-convert-pdfs-into-searchable-key-words-with-python-85aab86c544f]

Rev 0.1 Several issues are obvious:
1) parts of sentences between punctuations are showing up as a word; individual words are not being seperated
2) need to isolate title, author, affiliation, figure captions etc fields from the extracted text

Rev 0.2 [this was useful:https://stackoverflow.com/questions/34837707/extracting-text-from-a-pdf-file-using-python]
1) using textract rather than pyPDF2 to extract text from pdf solves the word recognition issue
2) still need to address issue #2 of rev 0.1
