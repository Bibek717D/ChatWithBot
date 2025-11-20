Java Chatbot 

Overview:
A simple rule-based chatbot built in Java using Maven.  
It responds to keywords like "resume", "interview", "internship", and "job" with helpful answers.

This project is designed to demonstrate Java programming, collections (HashMap), and basic user interaction.

Features:
- Rule-based keyword detection
- Predefined answers for internship & career-related queries
- Simple, extendable structure (just add more rules!)
- Runs directly with Maven (`mvn exec:java`)

How to Run:
Make sure you have Java 17+ and Maven installed.

-Navigate
cd ai-chatbot

-Compile
mvn clean compile

-Run
mvn exec:java -Dexec.mainClass="com.chatbot.App"

Sample Interaction:
Chatbot: Hello! I’m your AI chatbot. Type 'bye' to exit.
You: hello
Chatbot: Hi there! How can I help you?

You: interview
Chatbot: Common questions: Tell me about yourself, strengths/weaknesses, and project experience.

You: internship
Chatbot: Internships are a great way to gain experience. Do you want tips on resumes or interviews?

You: bye
Chatbot: Goodbye! Have a great day.


<img width="1460" height="841" alt="ss" src="https://github.com/user-attachments/assets/d0b182f8-7595-42a4-870f-de778cb822c6" />

Future Improvements:
- Adding more keywords for broader conversation
- Saving chat history into a file (`chatlog.txt`)
- Supporting JSON-based responses for easier updates
- Adding menu options (e.g., press 1 for resume tips, 2 for interview tips)


Author:
Bibek Dhakal 
A CS Undergrad student  

