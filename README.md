# 🩺 HealthAI - Intelligent Healthcare Assistant  

An AI-powered healthcare communication platform that enables seamless dialogue about wellness concerns.  
Patients can interact with the assistant, provide medical history, and receive personalized insights.  

---

## 🚀 Features
- 24/7 patient support with AI-powered chatbot  
- Patient profile (name, age, gender, medical history, medications, allergies)  
- Context-aware responses with conversation memory  
- Gradio-based interactive UI  
- Built on `transformers` and `torch`  

---

## 📦 Installation  

Clone the repo and install dependencies:  


git clone https://github.com/your-username/healthai-assistant.git
cd healthai-assistant

History Tracking

Patient Profile Memory: Each session keeps track of patient demographics, medical history, allergies, and medications.

Conversation Logs: Chat history is maintained within the session to preserve context for follow-up questions.

AI Context Retention: The assistant considers past inputs during response generation, creating continuity in conversation.

🔄 Workflow

User Inputs Profile

Patient fills in name, age, gender, medical history, medications, allergies.

Chat Initialization

User enters their health question in the chatbot.

AI Processing

Model (ibm-granite/granite-3.2-2b-instruct) receives input + profile context.

AI generates a personalized response.

Response Delivery

Gradio interface displays response in the chat window.

Chat history is updated for future context.

Iteration

Patient continues the conversation with multiple queries.

📸 Screenshots
Patient Chat Page

(Sample UI)


Analytics Dashboard (Future Scope / Enhanced Feature)

(Optional for future upgrade)


🚀 Feature Enhancements

Planned improvements for next versions:

📊 Health Analytics Dashboard

Heart rate, blood pressure, glucose levels, symptom frequency.

AI-generated health insights with trend analysis.

🧠 Smarter Context Retention

Store multi-session history using database integration (SQLite / MongoDB).

📱 Multi-Platform Support

Deploy on web, mobile, and cloud (Hugging Face Spaces, Colab, or AWS).

🔔 Notifications & Alerts

Reminders for medications or follow-ups.

🌐 Language Support

Multilingual healthcare assistant for global accessibility.
Feature Scope

The HealthAI Assistant project is designed to support patients with personalized, AI-driven healthcare interactions.

🔹 Core Features

Patient Profile Management

Collects and stores patient details such as name, age, gender, medical history, medications, and allergies.

AI-Powered Chat Support

Provides real-time responses to patient health-related queries.

Maintains conversational context for more meaningful dialogue.

Health Insights Generation

Summarizes responses with algorithmically generated recommendations.

Ensures context-based accuracy using patient data.

Interactive User Interface

Built with Gradio for easy patient interaction.

Sidebar for profile input + main chat window for communication.

Scalable Backend

Utilizes Hugging Face Transformers + PyTorch for LLM-based responses.

Model can be swapped/upgraded without UI changes.

🔹 Out of Scope (Not covered in this version)

Real-time medical diagnosis or prescription generation

Integration with Electronic Health Records (EHR) systems

Emergency medical alerts or remote monitoring

HIPAA/GDPR-compliant data storage
