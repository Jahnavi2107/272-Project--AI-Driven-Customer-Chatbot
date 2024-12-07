# **AI Chatbot for Flight Customer Support**

The AI Chatbot for Flight Customer Support is designed to automate customer interactions in the travel industry by using Natural Language Processing (NLP) to understand and respond to user queries. The chatbot assists with tasks like flight search, PNR verification, and flight status inquiries. It integrates with backend services to retrieve real-time data and provide meaningful responses. The chatbot operates 24/7, enhancing customer satisfaction and reducing operational costs.

---
Deployement Link: https://rad-crumble-2cf4a6.netlify.app/

Report Link: https://drive.google.com/file/d/1sRNeP3qG2GJPkdg9zhB5IFyDuTtgPRxE/view?usp=sharing

---
## **Project Overview**  
This chatbot is tailored for the airline industry, offering:
- Dynamic flight search based on user preferences (source, destination, date).
- Real-time PNR verification to check booking details.
- Flight status inquiries using flight numbers.
---

## **Technologies Used**  
### **Frontend**  
- React: For building the chatbot interface.

### **Backend**  
- Flask (Python): Handles API requests, manages database interactions, and connects with NLP services.

### **AI Services**  
- Google Dialogflow: For natural language understanding and intent recognition.

### **Database**  
- MySQL: Stores flight data, PNR records, and conversation logs.

---

## **Use Cases**  
1. **Automated Query Handling:** The chatbot handles tasks like:
   - Searching for available flights.
   - Verifying Passenger Name Records (PNR).
   - Providing flight status updates.
2. **24/7 Availability:** Ensures round-the-clock support, reducing dependency on human agents.  
---

## **Architecture**  
1. **Frontend (React):** Provides an intuitive chatbot interface for customers.  
2. **AI Engine:** Dialogflow is used for intent detection, handling user queries dynamically.  
3. **Backend (Flask):**  
   - Manages API endpoints for flight search, PNR verification, and chat interactions.  
4. **Database (MySQL):** Stores flight information, PNR data.
![image](https://github.com/user-attachments/assets/22698d0a-877f-4bb0-a9b5-36dc5ee7f90b)
---

## **Explanation**  
1. **Chat Interface:** The chatbot interface (React) allows users to enter queries. These are passed to the Flask backend via API calls.  
2. **NLP Processing:** The backend connects to Dialogflow for interpreting user input and identifying intents.  
3. **Data Retrieval:** Based on the identified intent, the backend queries the MySQL database for relevant information (e.g., flights, PNR details).  
4. **Response Generation:** The backend formats the retrieved data and sends it to the chatbot interface. If the query is unresolved, it escalates to human support.

---

## **Deployment**  
### **Using Heroku**  
The chatbot is deployed on Heroku for easy scalability and accessibility.  

### **Steps to Deploy on Heroku:**  
1. **Prepare the Application:**
   - Ensure all dependencies are listed in `requirements.txt`.
   - Include a `Procfile` to define the entry point of the Flask app:
     ```plaintext
     web: python app.py
     ```

2. **Set Up the Heroku Environment:**
   - Install the Heroku CLI.
   - Log in to Heroku:
     ```bash
     heroku login
     ```

3. **Deploy the Application:**
   - Initialize a Git repository (if not already done):
     ```bash
     git init
     ```
   - Add and commit all changes:
     ```bash
     git add .
     git commit -m "Initial Heroku Deployment"
     ```
   - Create a Heroku app:
     ```bash
     heroku create
     ```
   - Push the application to Heroku:
     ```bash
     git push heroku main
     ```
   - Set environment variables (e.g., database credentials, Dialogflow keys) using:
     ```bash
     heroku config:set KEY=VALUE
     ```

4. **Access the Deployed App:**
   - Use the provided Heroku app URL to access your chatbot.

---

## **Future Enhancements**  
1. **Real-Time API Integration:** Add third-party APIs for live flight updates.  
2. **Enhanced Personalization:** Use AI to recommend flights based on customer preferences and history.  
3. **Analytics Dashboard:** Build a dashboard to visualize customer interactions and improve service.

---

## **Contributors**  
- **Himaswetha** - Backend and Database
- **Jahnavi Burla** - Frontend Development and Deployment  
- **Vinuta and Harshitha** - Database, Dialogflow and Integration  
