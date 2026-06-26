# CodeAlpha - Basic Chatbot (Python Internship Task)

A simple **rule-based chatbot** built in Python that responds to a fixed set
of user inputs using `if-elif` logic.

## 🎯 Goal
Build a chatbot that can understand basic greetings and simple questions,
and reply with predefined responses — no AI/ML involved, just clean
conditional logic.

## 🛠️ Concepts Used
- `if-elif` conditional logic
- Functions
- `while` loop (to keep the conversation going)
- Basic input/output handling

## 💬 Sample Conversation
Chatbot: Hi! Type 'bye' to end the chat.
You: hello
Chatbot: Hi! How can I help you today?
You: how are you
Chatbot: I'm fine, thanks! How about you?
You: what is your name
Chatbot: I'm a simple rule-based chatbot built in Python.
You: thanks
Chatbot: You're welcome!
You: bye
Chatbot: Goodbye! Have a great day.
## ▶️ How to Run
```bash
python3 chatbot.py
Type your message and press Enter. Type bye, exit, or quit to end
the chat.
📂 Supported Inputs
You type
Chatbot replies
hello / hi / hey
Hi! How can I help you today?
how are you
I'm fine, thanks! How about you?
what is your name / who are you
I'm a simple rule-based chatbot built in Python.
thanks / thank you
You're welcome!
bye / goodbye / exit / quit
Goodbye! Have a great day.
anything else
Sorry, I didn't understand that. Can you rephrase?
🚀 Future Improvements
Add more keyword patterns per intent
Use difflib/fuzzy matching for typo tolerance
Upgrade to an NLP-based or AI-powered chatbot (e.g. using the Anthropic API