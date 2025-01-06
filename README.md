# SwigMato-ChatBot

Developed a high-performance food delivery chatbot using Dialogflow, FastAPI, and MySQL to streamline real-time order management and tracking. Designed modular session-based workflows, automated database operations, and optimized error handling, reducing order processing time by 30% and enhancing user satisfaction with accurate, dynamic responses.

# Highlights of Technical Workflow:
Session Management: Extracts session IDs from Dialogflow contexts to manage user-specific orders.
Food Item Validation: Ensures accurate order processing by validating item names and quantities.
Database Transactions: Safeguards data integrity through robust transaction handling and rollback mechanisms in case of errors.
Custom SQL Functions: Optimizes total order price retrieval and next order ID computation for high-performance database queries.

# Technologies Used:
Dialogflow: Natural Language Processing for intent recognition.
FastAPI: High-performance Python web framework for API development.
MySQL: Database management for order storage and retrieval.
Python: Core programming language for backend development.

# Efficient Code Organization:

main.py: Orchestrates request handling, intent processing, and response generation.
generic_helper.py: Utilities for session ID extraction and string formatting for user-friendly responses.
db_helper.py: Handles all database operations, ensuring scalability and maintainability.
