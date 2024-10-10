# 272-Project--AI-Driven-Customer-Chatbot

**Project Overview**  
The AI Chatbot for Customer Support is designed to automate customer interactions by using Natural Language Processing (NLP) to understand and respond to user queries. The chatbot handles frequently asked questions (FAQs) and  basic troubleshooting. It integrates with backend services to retrieve real-time data and provide meaningful responses. When necessary, it escalates unresolved issues to human agents, ensuring 24/7 support while improving customer satisfaction and reducing operational costs for businesses.

**Persona Summary**   
Customers: Individuals seeking immediate help or answers to common issues without waiting for human support.  
Customer Support Teams: Support staff looking to reduce repetitive workload and improve response times.  
Managers: Leaders aiming to improve customer satisfaction and optimize support team productivity.

**Technologies Used**   
Frontend: React for building the chatbot interface.  
Backend: Spring Boot (Java) or Flask (Python) for managing requests, processing data, and interacting with the AI model.  
AI Services: Dialogflow, Rasa, or Hugging Face Transformers for NLP and intent recognition.  
Database: MongoDB or PostgreSQL for storing customer conversations and logs.  

**Use Cases**   
Automated Query Handling: The chatbot answers frequently asked questions (FAQs) and performs basic troubleshooting tasks.  
Escalation: When the chatbot can’t answer a question, it escalates to human support, handing off the conversation seamlessly.  
24/7 Availability: The chatbot is available at all hours, ensuring constant customer support.

**Architecture**    
Frontend (React): Customers interact with the chatbot via a user-friendly interface.  
AI Engine: The chatbot uses NLP services to understand and respond to customer queries.  
Backend (Spring Boot/Flask): Manages API calls, retrieves data from the database, and sends responses.  
Database: Stores historical chat logs and interactions.  
Optional Analytics: Data from conversations can be analyzed to improve chatbot performance and customer satisfaction.
![image](https://github.com/user-attachments/assets/da94521c-2404-4d69-b9ed-b95685686442)

**Explanation**    
Chat Interface: The chatbot interface (React or Angular) allows users to enter queries, which are passed to the backend.  
NLP Processing: The backend integrates with an NLP engine (Dialogflow/Rasa) to interpret user input and match it to an intent.  
Backend API: Handles logic, retrieves additional information (if needed), and interacts with the AI service for a response.  
Response: The backend sends the appropriate response back to the chatbot interface for the customer.

**Deployment**   
Cloud Services: AWS for scalable deployment.  
Continuous Improvement: Regularly update the model with new training data based on real conversations.

