This project is a travel-focused chatbot named GlobeGuru built using Python, Natural Language Processing (NLP), and the Streamlit framework. Here's a detailed explanation of its components and functionality:

**🔍 How It Works**
User Interaction:
Users enter queries into the chat interface.
The chatbot processes input and matches it with the closest intent.
Response Generation:
Machine learning models predict the intent.
Responses are fetched dynamically from the intents.json file.
Model Training:
Data from intents.json is preprocessed using TF-IDF Vectorizer.
Logistic Regression and Random Forest Classifier are used for training.
Chat History Logging:
Conversations are saved in chat_log.csv for future analysis.

**🚀 Features**
**Interactive Chat Interface:**
Dynamic responses to user queries.
Real-time chat history display.
**Travel Assistance:**
Covers topics like destinations, budgeting, and travel tips.
Provides recommendations and general advice.
**Model Evaluation:**
Evaluate chatbot performance with metrics like accuracy and classification reports.
**Chat History Management:**
Logs conversations for reference and analysis.
**Customizable Design:**
Built with Streamlit and custom CSS for an engaging user interface.

**📂 Project Structure**
app_travelbot.py: Main application file for Streamlit interface.
chatbot.py: Core logic for chatbot training and response generation.
intents.json: Dataset defining user intents, patterns, and responses.
style.css: Custom CSS for enhanced UI design.
chat_log.csv: Stores conversation history.

**🛠 Technologies Used**
**Programming Language:**
Python
Frameworks & Libraries:
Streamlit for UI
Scikit-learn for Machine Learning
NLTK for NLP
TF-IDF Vectorizer for text processing
Logistic Regression and Random Forest Classifier for intent classification
**Data:**
Intents structured in a JSON format for predefined responses.

**🎯 Future Enhancements**
Intent Identification: Improve contextual understanding.
Emotion Detection: Add emotion-based responses.
Multi-language Support: Enable multilingual conversations.
Real-Time Data Integration: Incorporate APIs for weather, currency conversion, and more.
