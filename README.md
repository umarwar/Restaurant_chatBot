# Restaurant_chatBot

Developed a restaurant chatbot backend using FastAPI to assist customers with ordering. The chatbot handles various intents such as adding items to an order, removing items, completing orders, and tracking orders. It maintains ongoing orders in a session-based structure, interacts with a database for order management, and provides real-time responses to user queries with JSON responses. The backend efficiently manages order data, tracks order statuses, and ensures smooth communication between users and the restaurant system.

### Running the Backend

To start the FastAPI backend:

1. **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Restaurant_chatBot
    ```

3. **Start the FastAPI server:**
    ```bash
    uvicorn main:app --reload
    ```
