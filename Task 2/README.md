AI Health Assistant Chatbot

Overview
AI Health Assistant Chatbot is an intelligent healthcare support system built using Python, Google Gemini API, and Gradio. The project helps users get quick, simple, and understandable answers to general health-related questions through a conversational chatbot interface.
This chatbot is designed for educational and informational purposes only and does not replace professional medical consultation. It focuses on safe healthcare guidance and blocks dangerous or sensitive medical topics.

Features
AI-powered health question answering
Built using Google Gemini (Gemini 2.5 Flash)
Gradio-based interactive chatbot interface
Safety filter for harmful medical queries
Quick replies for greetings and common messages
Structured prompt engineering for better responses
User-friendly and beginner-friendly design

Technologies Used
Python
Google Generative AI
Gemini 2.5 Flash
Gradio
Jupyter Notebook
Project Structure

Health_Chatbot.ipynb
│
├── Install Dependencies
├── Import Libraries
├── Configure Gemini API
├── Define System Prompt
├── Safety Check Function
├── Quick Reply Function
├── Main Chatbot Function
└── Gradio Interface

Installation
Step 1: Clone Repository
git clone https://github.com/your-username/health-chatbot.git
cd health-chatbot

Step 2: Install Dependencies
pip install -r requirements.txt

Step 3: Add Gemini API Key
genai.configure(api_key="YOUR_API_KEY")

Step 4: Run the Notebook
Open Health_Chatbot.ipynb and run all cells.

Step 5: Launch Application
demo.launch(debug=True)

Example Questions
What causes a sore throat?
Why do headaches happen?
How can I improve my sleep?
What are symptoms of a cold?
How can I stay hydrated?

Safety Notice
This chatbot does not provide:
Emergency medical advice
Prescription recommendations
Overdose guidance
Self-harm related support
Serious disease diagnosis

Users are advised to consult healthcare professionals for medical emergencies.

Future Improvements
Voice input and output
Multi-language support
Symptom checker
Disease prediction system
Doctor appointment integration
Hospital recommendation system
Patient history tracking
