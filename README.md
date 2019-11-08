# FE595-Midterm
## Project Description:
For this project, our group created 6 different NLP web services which can run on AWS as a flask app.
More details about the function of different services are listed below.
### Translate
This function can translate any language into English. If you input English, the result will still be English. 
Notice: If you are willing to translate chinese, then your original text must contain at least 3 chinese characters.
### Summarize
This function can make a summary of an article or some paragraphs.
Notice: The text to be processed must contain at least 3 complete sentences.
### Sentiment analyse
This function analyse the sentiment of text imput. This fucntion returns a number between -1 to 1, in which -1 represnts negative and 1 represnts positive.
### Keyword extraction
This function extracts the top3 keywords of the text inpute and returns them.

### Spell correction
Spell correction requires the user to type a paragraph of text, correct the wrong spelling, and tell the user which words in the paragraph are correctly spelled.

### Spam mail recognition
The function of this service is that the user enters an email and the system uses Naive Bayes classifier to identify whether the email is Spam. 
When the result is 1, it is Spam; otherwise, it is not Spam.


## Group contribution:
### Shijie Cai
1.Contributed to the Sentiment analyze service and Keyword extraciton service. 
2.Supported the main framework of html file.
3.Tested the final results.

### Yinchi Chen
1.Contributed to the Spell correction service and Spam mail recognition service. 
2.Checked the final codes and html file.
3.Tested the final results.

### Kan Wu
1.Contributed to the Translate service and Summarie service. 
2.Combined all the team's code into one final file and finished the final html.
3.Tested the final results on AWS.
