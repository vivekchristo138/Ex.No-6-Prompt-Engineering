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


<img width="742" height="218" alt="Screenshot 2026-03-22 150113" src="https://github.com/user-attachments/assets/a4d269f4-a1aa-4194-850a-14ba77879ca8" />


<img width="746" height="275" alt="Screenshot 2026-03-22 150132" src="https://github.com/user-attachments/assets/d6d6e3be-35b7-4128-96df-8e536e27d9a8" />

Result: 

 Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools was written and implemented successfully.
