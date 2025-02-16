# AST_Consulting
Python Developer Skill assessment test.
📌 Project Overview
This project is a web scraping and data management system that:
Scrapes Python Developer job listings from Indeed.com.
Stores the scraped data in a MongoDB database.
Provides a Django admin panel where users can search, edit, and delete job listings.
Uses NumPy to calculate the average salary for Python Developers in a specified city.

🛠 Tech Stack
Python (for scripting & backend development)
BeautifulSoup4 (for web scraping)
Requests (for making HTTP requests)
MongoDB (for storing job listings)
Django (for admin panel & web framework)
NumPy (for salary calculations)
🚀 Features
✅ Web Scraping: Collects job postings dynamically from Indeed.com.
✅ MongoDB Integration: Saves scraped job data in a structured database.
✅ Django Admin Panel: Allows users to search, edit, and delete job entries.
✅ Salary Analysis: Uses NumPy to compute the average salary of Python developers.
✅ User Authentication: Secured Django admin interface for managing job data.

📂 Project Structure
📦 job_scraper_project
 ┣ 📂 job_scraper_app
 ┃ ┣ 📜 models.py      # Defines Job model
 ┃ ┣ 📜 views.py       # Handles data processing
 ┃ ┣ 📜 admin.py       # Configures Django Admin Panel
 ┃ ┣ 📜 scraper.py     # Web scraping script
 ┃ ┣ 📜 database.py    # MongoDB connection & data storage
 ┣ 📜 requirements.txt  # Dependencies
 ┣ 📜 manage.py        # Django project manager
 ┣ 📜 README.md        # Documentation (this file)

🔧 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/job_scraper_project.git
cd job_scraper_project
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Configure MongoDB
Replace <username> and <password> in database.py with your MongoDB credentials:
MONGO_URI = "mongodb+srv://<username>:<password>@cluster.mongodb.net/job_listings_db"
4️⃣ Run Web Scraper
python scraper.py
5️⃣ Start Django Server
python manage.py runserver
6️⃣ Access Admin Panel

Create a superuser:
python manage.py createsuperuser
Then, log in at:
http://127.0.0.1:8000/admin/
📊 Salary Analysis
To calculate the average salary, run:
python salary_analysis.py

🎯 Future Improvements
🔹 Support multiple job platforms (LinkedIn, Glassdoor, etc.).
🔹 Deploy Django project on Heroku or AWS.
🔹 Improve data visualization with Matplotlib or Dash.

👨‍💻 Author

Developed by Ishan Mishra

📧 Contact: ihrm.aiml@gmail.com
