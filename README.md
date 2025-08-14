# Expense-Tracking-system-using-Python
## Overview
Personal Finance Tracker is a full-stack web application designed to simplify expense tracking, management, and analysis. With a clean interface, advanced analytics, and secure data handling, it empowers users to take control of their finances.
*******************************************************************************************************************************************************************************************************************
## Key Features
* Expense Tracking: Seamlessly add, edit, or remove expense records.
* Paginated Views: Browse expenses by date with paginated results (5 entries per page).
* Category Insights: Analyze spending by category over custom date ranges with charts and tables.
* Monthly Breakdowns: View monthly expense trends for selected categories and years.
* Data Integrity: Validates inputs, prevents duplicates, and restricts categories to predefined options.
* Operation Logging: Tracks backend activities for debugging and monitoring.
* Test Data Generator: Populates the database with sample data for quick testing.
* Unit Testing: Ensures backend reliability with comprehensive Pytest coverage.
*******************************************************************************************************************************************************************************************************************
## Project Structure
<img width="1195" height="802" alt="image" src="https://github.com/user-attachments/assets/db6caadb-9913-43c9-a47c-6fb3c73ff93d" />

*******************************************************************************************************************************************************************************************************************
## Project Structure
* frontend/: Contains the Streamlit application code.
* backend/: Contains the FastAPI backend server code.
* tests/: Contains the test cases for both frontend and backend.
* requirements.txt: Lists the required Python packages.
* README.md: Provides an overview and instructions for the project.
******************************************************************************************************************************************************************************************************************
## My Streamlit App

<img width="933" height="712" alt="image" src="https://github.com/user-attachments/assets/3d1ee873-b95c-449f-a0d4-3aa1b31d46ed" />

***************************************************************************************************************************************************************************************
## A Demo Video

[![Watch the video](https://img.youtube.com/vi/71J7QsYBJ4I/0.jpg)](https://youtu.be/71J7QsYBJ4I)
**************************************************************************************************************************************************************************************************
## Skills Gained
* Integrating Mysql with python
* Using Streamlit to design the frontend and making HTTP calls from the frontend to the backend
* Used FastAPI as a backend to run the server
* Managing HTTP requests with Postman API
**********************************************************************************************************************************************************************************************************
## Project Explanation
### These are the steps I followed in my project.
* Integrated MySQL with Python: Created a set of functions which is used for CRUD operations.
* Setting up API Endpoints: Used FastAPI instead of Flask because it has nice documentation and an auto debugging process.
* Added logging: Used Logging to track our process; if there is any issue or error, we can catch it using these logs.
* Verified the API calls through POSTMAN: Used Postman to check the response given by 'GET' and 'POST' requests.
* Frontend Development using Streamlit: In Streamlit, I used API endpoints to call the backend and get the response from the FastAPI backend.
*****************************************************************************************************************************************************************************************************************
## Running the App
1. Launch the Backend

        cd backend
        uvicorn api_server:app --reload



2. Launch the Frontend
   In a new terminal:

       cd frontend
       streamlit run main.py

 3. Access the App

Visit              

      http://localhost:8501 in your browser.
*******************************************************************************************************************************************************************************************************************************
## App Tabs
### Tab 1: Manage Expenses
* View expenses for a chosen date with pagination (5 entries/page).
* Shows total entries and pages for the date.
* Add: Enable "Add New Expense", input details, and submit. Duplicates are blocked.
* Edit: Modify existing records and confirm changes.
* Delete: Select records via checkboxes and confirm deletion.
### Tab 2: Category Insights
* Visualize spending by category for a selected date range.
* Includes bar charts and a table with totals and percentages.
### Tab 3: Monthly Insights
* Analyze expenses by month for a chosen year and categories.
* Displays charts and a detailed table.
*******************************************************************************************************************************************************************************************************************************

## Security & Validation
* Category Limits: Restricts to predefined categories.
* Input Validation: Ensures accurate and complete data.
* Logging: Records backend operations for transparency.
* Testing: Validates backend functions with Pytest.
****************************************************************************************************************************************************************************************************************************
## Contributing
To contribute, please submit issues or pull requests for enhancements or fixes.
************************************************************************************************************************************************************************************************************************
📧 [Email Me](mailto:connectingsrl@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/sahajahanur-laskar/)













  
                     



   























