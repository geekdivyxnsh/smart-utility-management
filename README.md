Smart Utility Management is a full-stack application designed to efficiently track and manage utility consumption, including electricity, water, and gas. The system provides real-time analytics, bill generation, and notification alerts to help users optimize their usage and reduce costs.

Tech Stack

Frontend
HTML, CSS, JavaScript – For building the UI
Bootstrap – For responsive design

Backend
Python (Flask/Django) – For handling API requests and business logic
Flask RESTful API – For building REST APIs
Jinja2 – For template rendering (if Flask is used for UI)

Database
MySQL/PostgreSQL – For storing user data, utility usage, and billing details
SQLAlchemy – ORM for database interactions

Authentication & Security
JWT (JSON Web Tokens) – For secure authentication
Flask-Login / OAuth – User authentication & session management
Argon2/Bcrypt – Password hashing for enhanced security

Other Tools & Libraries
Pandas, NumPy – For data analysis and processing
Matplotlib, Seaborn – For visualizing consumption trends
Celery + Redis – For scheduling background tasks (like bill reminders)
Flask-Mail / Twilio API – For email and SMS notifications

Features
User Authentication: Secure login/logout functionality
Utility Consumption Tracking: Monitor electricity, water, and gas usage
Automated Bill Calculation: Generate utility bills based on consumption patterns
Real-Time Data Analytics: Graphs and reports for consumption trends
Alerts & Notifications: Get notified about abnormal usage or due bills
Admin Dashboard: Manage users, services, and billing settings

Installation Guide
1. Clone the Repository
git clone https://github.com/geekdivyxnsh/smart-utility-management.git
cd smart-utility-management

2. Set Up Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate  
venv\Scripts\activate     

3. Install Dependencies
pip install -r requirements.txt

4. Configure Database
Update config.py with your MySQL/PostgreSQL database credentials.
Initialize the database:
python db_setup.py

5. Run the Application
python app.py
Open http://localhost:5000 in your browser to access the application.



