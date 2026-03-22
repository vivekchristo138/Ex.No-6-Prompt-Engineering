Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

Explanation:

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.

python code
```import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = input("Enter a review:")
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

output
<img width="746" height="275" alt="image" src="https://github.com/user-attachments/assets/fd37a32c-0c6e-4e50-ac60-046f9d64f06a" />
<img width="746" height="275" alt="image" src="https://github.com/user-attachments/assets/82253e15-07b2-4875-a325-93e0a7b9c926" />

Result: 

 Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools was written and implemented successfully.
