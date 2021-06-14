# Plagiarism-Checker

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/3512966900d04d85952cc2b0fe33ce3e)](https://app.codacy.com/gh/tkoppop/Plagarism-Checker?utm_source=github.com&utm_medium=referral&utm_content=tkoppop/Plagarism-Checker&utm_campaign=Badge_Grade_Settings)

Using python I have created a plagiarism checker that simply tests the similariy between all .txt files in a folder. It uses Vectorizer to set a numerical value to all files based on the words used, and compares it with cosine similarity (based of cosine law). In other words, the file gets turned into a vector, and the cosine similarity reads the angle between the two vectors and lists that as the % similarity. This program will try all combinations of files and print them out at the end. 

Jan 12, 2021:
  So far the app.py only can access files within the same folder. I am hoping to implement it with google api, where I can search the actual files on that api, and pull about 10 links that are similar and output those similarities. It is also possible to tell the user that there are links with high similarity, and flag certain key words.
