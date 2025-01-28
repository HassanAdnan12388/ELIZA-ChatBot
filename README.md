# ELIZA-ChatBot


## 📌 Project Overview
Aleeza is a rule-based chatbot inspired by ELIZA, the first-ever chatbot developed in 1966 by Joseph Weizenbaum. This project implements a simplified version of ELIZA using regular expressions and predefined response templates to simulate a conversation.

## 🛠️ Technologies Used
- **Python**: Core programming language
- **Regular Expressions (re)**: Used for pattern matching in user input
- **JSON**: Stores predefined chatbot responses
- **Random Module**: Selects varied responses for natural interaction

## 📖 How It Works
Aleeza operates by analyzing user input and responding based on predefined rules:
1. **Reflection Table**: Converts first-person pronouns ("I am") into second-person equivalents ("You are").
2. **Response Table**: Uses regex to match patterns and generate responses dynamically.
3. **Pattern Matching**: Identifies common sentence structures and generates appropriate responses.



## 📝 Example Interaction
```
User: I am feeling sad.
Aleeza: How long have you been feeling sad?

User: My friend is ignoring me.
Aleeza: Why do you think your friend is ignoring you?
```


## 🎯 Future Improvements
- Expand response table for more natural conversations
- Implement a GUI-based chatbot interface
- Integrate machine learning for advanced responses



