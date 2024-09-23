# HR-Data-using-SQL-and-Python
This project is an HR data management system that uses Python and SQL to track and manage information related to programmers, software they use, and their educational background. It provides a simple interface for entering and storing key details about programmers, their proficiency, and other associated data like software and education.

The data is collected using `Streamlit` and can be stored in a SQL database for further processing, analysis, and retrieval.

# Key Features
* **Programmer Management** : Input detailed information about a programmer, including personal data and proficiency in programming languages.
* **Software Management**: Manage the software that programmers use, including information on cost, units, and development history.
* **Education Management**: Track educational background and courses undertaken by programmers, linked with their respective IDs.

# Tech Stack
* **Frontend**: Streamlit for user input and interface.
* **Backend**: Python for data handling and SQL integration for data storage.
* **Database**: SQL for storing and managing data.

# Installation
## Prerequisites
Make sure you have Python installed on your machine. You also need the following Python libraries:
``` bash
pip install streamlit
pip install sqlite3
```
## Running the Application
* Clone the repository:
``` bash
git clone https://github.com/yourusername/hr-data-management.git
```
* Navigate into the project directory:
``` bash
cd HR-Data-using-SQL-and-Python
```
* Run the Streamlit app:
``` bash
streamlit run programmer.py
```
# Files Structure
* **programmer.py**: Handles input for programmer details such as name, gender, phone number, email, date of birth, date of joining, proficiency in programming languages, and salary.
* **software.py**: Manages information about software, including software name, development environment, cost price, sell price, and units available.
* **education.py**: Stores education-related data for programmers, linking them with their programmer ID and software ID, and tracks course information and associated fees.

# Usage
1. **Programmer Input** (`programmer.py`)
* First Name
* Last Name
* Gender
* Phone Number
* Email ID
* Date of Birth
* Date of Joining
* First and Second Proficiency in Programming Languages
* Salary
2. Software Input (software.py)
* Programmer ID
* Software Name
* Developed In
* Cost Price
* Sell Price
* Units
3. Education Input (education.py)
* Programmer ID
* Software ID
* Institute Name
* Course Name
* Course Fee

# SQL Database
The data input through the Streamlit forms is stored in an SQL database, which can be used to manage, update, and retrieve HR-related data effectively.
## SQL Tables
* **Programmer Table**: Contains all programmer-related data.
* **Software Table**: Stores information about software.
* **Education Table**: Manages educational background and course details.

# Future Enhancements
* Add search and filter functionality to retrieve and display stored data.
* Enhance UI with charts and graphical representation of data.
* Integrate authentication and role-based access control for better security.
* Implement cloud-based database support for scalability.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Contribution
Feel free to fork this repository, make improvements, and submit a pull request. All contributions are welcome!
