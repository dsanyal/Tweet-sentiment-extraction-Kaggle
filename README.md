# Tweet sentiment extraction


From Kaggle:
"My ridiculous dog is amazing." [sentiment: positive]
With all of the tweets circulating every second it is hard to tell whether the sentiment behind a specific tweet will impact a company, or a person's, brand for being viral (positive), or devastate profit because it strikes a negative tone. Capturing sentiment in language is important in these times where decisions and reactions are created and updated in seconds. But, which words actually lead to the sentiment description? In this competition you will need to pick out the part of the tweet (word or phrase) that reflects the sentiment.


#### What is the task?

- Given the tweet text and the sentiment of the tweet, the task at hand is to extract the text from the tweet that reflects the sentiment. How interesting!
- One can formulate the problem as a **question-answering task**, where the sentiment is the *(short)* question, the tweet itself is the context and the selected text is the answer.


I trained a BERT model with a Q&A head to solve the problem. This achieved a score of 0.684 on the public LB.
