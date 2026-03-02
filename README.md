# IntelliTutor: AI-Powered Personal Tutor Bot

**IntelliTutor** is an intelligent chatbot designed to provide academic support to students in fields like Cyber Security, Machine Learning, Data Science, AI, and Networking. It combines rule-based logic, machine learning, and a semantic knowledge graph to deliver accurate, personalized, and sentiment-aware responses.

---

## Features

- **Natural Language Processing (NLP):** Processes user queries using SpaCy to extract keywords and understand intent.
- **Knowledge Graph:** Uses NetworkX to represent relationships between topics, concepts, and courses.
- **Sentiment Analysis:** Adjusts response tone based on detected sentiment using Multinomial Naive Bayes with TF-IDF vectorization.
- **Best First Search Algorithm:** Efficiently retrieves relevant answers from the knowledge graph.
- **Interactive GUI:** Built with Tkinter, supporting theme switching (Light, Dark, Blue), session management, and real-time responses.
- **Teach Bot Functionality:** Users can add new questions and answers to expand the knowledge base.
- **Session Management:** Save, reset, and review chat sessions.
- **Auto-Suggestions:** Provides query suggestions as the user types.

---

## Installation

1. Clone the repository:  
   git clone https://github.com/yourusername/intellitutor.git

Navigate to the project folder:

cd intellitutor

Install required Python packages:

pip install -r requirements.txt

Run the bot:

python main.py
Usage

Enter a query in the input field and press Send.

Switch themes between Light, Dark, and Blue from the GUI.

View previous chat history or reset sessions as needed.

Use the Teach Bot feature to add new questions and answers dynamically.


---

## Challenges

Designing a comprehensive knowledge graph and handling malformed CSV data.

Achieving high sentiment analysis accuracy with limited data.

Optimizing Best First Search for relevance and performance.

Maintaining GUI responsiveness during dynamic updates.


---

## Limitations

Small sentiment dataset limits nuanced sentiment detection.

Knowledge base is currently static and local (CSV-based).

Search may miss deeply linked nodes in the graph.

Tkinter GUI may lag with large datasets.

No web integration for fetching external information.


---

## Future Enhancements

Improve sentiment analysis using larger datasets or transformer models.

Integrate web search to fetch answers beyond the local knowledge graph.

Replace CSV with a database (e.g., SQLite) for scalability.

Add voice input (speech-to-text) for hands-free interaction.

Support multiple languages.

Implement adaptive learning via reinforcement learning.

Provide API integration for dynamic knowledge updates.


---

## Conclusion

IntelliTutor offers a robust, interactive platform for personalized academic support. By integrating NLP, machine learning, and a semantic knowledge graph, it provides accurate answers, adaptive responses, and a friendly GUI. Future enhancements will further expand its capabilities, making it a versatile tool for students in technical fields.
