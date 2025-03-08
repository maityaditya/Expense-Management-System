# Expense Management System

This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.


## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.

## Sample Pictures

-**Add/Update/**
![Image](https://github.com/user-attachments/assets/4a7560cf-fea8-467a-a985-ea6c299177f6)

-**Analytics by categories/**
![Image](https://github.com/user-attachments/assets/b82dfdb7-445d-43bf-8a25-31320f4ff5a4)

-**Analytics by months/**
![Image](https://github.com/user-attachments/assets/0b5887a1-4f65-4270-8238-ca7c6211cb26)

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/maityaditya/Expense-Management-System.git
   cd Expense-Management-System
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
