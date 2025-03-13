# Expense Management System

This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.


## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.

**## UI**
- ![image](https://github.com/user-attachments/assets/ede1546d-63d0-4d88-98eb-0e6aac248b0a)
- ![image](https://github.com/user-attachments/assets/c81fbfdf-1915-47d1-abf7-026ae2630c25)
- ![image](https://github.com/user-attachments/assets/dafa8cc2-51f2-40ac-b675-cbd6f6017cab)





## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
