Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

Explanation:

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.

code used for positive output:
```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = "This smartphone offers outstanding battery life and an intelligent AI camera that captures stunning photos."

print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)

# Insight generation
if sentiment['compound'] > 0:
    print("\nInsight: The review is positive and suitable for marketing promotion.")
else:
    print("\nInsight: The review tone is neutral or negative.")
```
positive output:
<img width="1250" height="193" alt="image" src="https://github.com/user-attachments/assets/5d595edd-2fb7-4fab-9d4d-6d44182631ab" />
negative output:
<img width="1207" height="184" alt="image" src="https://github.com/user-attachments/assets/9bb68c86-28dc-4769-b7b6-4426cfa8a139" />

RESULT:
The python program executed successfully.

