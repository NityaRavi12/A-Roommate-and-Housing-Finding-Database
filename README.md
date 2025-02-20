# RoomNest: A Roommate and Housing Finding Database - README
RoomNest is a comprehensive database-driven platform designed to streamline the process of finding roommates and suitable housing, particularly for students transitioning to new universities.  It addresses the challenges of navigating diverse preferences, budgetary constraints, and the often disorganized nature of informal roommate search methods.

I. Overview

RoomNest connects students, landlords, and brokers within a structured online environment.  Students create detailed profiles outlining their preferences (budget, lifestyle, dietary restrictions, etc.), while landlords and brokers provide comprehensive property listings. The system employs a robust matching algorithm to connect compatible individuals, fostering a sense of community and reducing the friction associated with traditional roommate searches.

II. Key Features:

User Registration and Profiles:  Students, landlords, and brokers register, creating detailed profiles that include essential information and preferences.  Students can specify their preferred housing type, budget, and lifestyle choices.  Landlords and brokers provide complete property descriptions, including amenities, utilities, and proximity to universities.

Property Listings Management: Landlords and brokers can easily manage their listings, adding, updating, or removing properties as needed.  The system facilitates efficient organization and dissemination of housing options.

Advanced Search and Filtering: Students can use sophisticated search and filter options to refine their search based on various criteria, including price range, location, amenities, and roommate preferences.

Roommate Matching Algorithm: The core of RoomNest is a sophisticated algorithm designed to match students based on compatibility, ensuring a higher likelihood of successful roommate pairings.

Secure Communication (Future Feature):  A planned secure in-app messaging system will enable direct communication between students and landlords/brokers, fostering transparent interactions and simplifying the process of arranging viewings or lease agreements.

Data Integrity and Security:  The platform utilizes a MySQL relational database, implementing robust data validation and security measures to ensure the accuracy and confidentiality of user information and property details.

III. Technology Stack:

Backend: Python 3.10 (Flask, SQLAlchemy, pymysql) -  Provides a robust framework for handling database interactions, user authentication, and the matching algorithm. SQLAlchemy handles database ORM (Object Relational Mapping), facilitating efficient database operations.  Flask manages the web application framework and APIs.  PyMySQL manages connection to the MySQL database.

Database: MySQL - A relational database system providing data integrity and efficient querying capabilities.

Frontend: Text-based Menu-Driven Interface - A simple, user-friendly command-line interface guides users through the registration, search, and property management processes.  This approach allows for focused interaction and data validation, minimizing potential errors.

Database Management Tool: MySQL Workbench - A comprehensive database administration tool used for creating, managing, and monitoring the database.

Other Libraries: NumPy (numerical processing), Matplotlib (data visualization—for future data analysis features), Getpass (secure user credential handling).

IV. Setup Instructions:

Prerequisites: Ensure that MySQL and Python 3 are installed on your system.

Install Python Libraries: Use pip to install the necessary Python libraries:
pip install pymysql Flask SQLAlchemy numpy matplotlib getpass
Database Setup:

Import the provided SQL database dump (roomnest.sql) to create a new database (e.g., RoomNestDB). This creates the necessary tables and stored procedures.
You can use MySQL Workbench or the command-line tool (mysql) to execute the SQL script.

Run the Application: Navigate to the application directory and execute:
python app.py 
(Use python3 app.py if necessary, depending on your Python installation.)

V. User Interaction:

The application features a menu-driven interface guiding users through registration, searching, and management functions.  Specific instructions are detailed within the application.

VI. Future Enhancements:

Mobile Application: Development of a mobile app to enhance accessibility and user experience.
In-App Messaging: Implementation of a secure in-app messaging system for seamless communication between users.
Data Analytics and Reporting: Development of reporting features to provide insights into user behavior, housing trends, and roommate compatibility.
Blockchain Integration: Exploring blockchain technology to enhance data security and immutability.
