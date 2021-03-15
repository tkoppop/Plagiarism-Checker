# Plagarism-Checker

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/3512966900d04d85952cc2b0fe33ce3e)](https://app.codacy.com/gh/tkoppop/Plagarism-Checker?utm_source=github.com&utm_medium=referral&utm_content=tkoppop/Plagarism-Checker&utm_campaign=Badge_Grade_Settings)

Using pythong, I have created a plagarism checker that simply tests the similariy between certain files in the same folder. It use Vectorizer to create a numerical value of the files, and implements cosine similarity based of cosine law. Basically the file gets turned into a vector, and the cosine similarity reads the angle between the two vectors and lists that as the similarity. 

Jan 12, 2021:
  So far the app.py only can access files within the same folder. I am hoping to implement it with google api, where I can search the actual files on that api, and pull about 10 links that are similar and output those similarities. It is also possible to tell the user that there are links with high similarity, and flag certain key words.
