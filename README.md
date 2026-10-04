# 🏫 SchoolOS — School Management System

**SchoolOS** is a simple school management system built with **Python and Streamlit**.

It provides a web-based interface for managing students, teachers, and student grades. The application stores data locally using a JSON file.

This is my **first Python project**, created to apply the Python and Object-Oriented Programming concepts I learned in a practical application.

## ✨ Features

- 📊 Interactive dashboard
- 👨‍🎓 Register students
- 👨‍🏫 Register teachers
- 📚 Add student grades
- 📈 Calculate student average scores
- 🔎 View student details
- 🔎 View teacher details
- 📧 Basic email validation
- 🚫 Prevent duplicate student roll numbers
- 🚫 Prevent duplicate teacher employee IDs
- 💾 Persistent data storage using JSON
- 🎨 Custom Streamlit UI

## 🛠️ Technologies Used

- **Python**
- **Streamlit** — Web application interface
- **JSON** — Local data storage
- **Pathlib** — File handling
- **ABC / Abstract Base Class** — Object-oriented design
- **HTML & CSS** — Custom UI styling
- **Git & GitHub** — Version control

## 📂 Project Structure

```text
ManagementApp/
│
├── app.py
├── main.py
├── school_data.json
└── README.md
```

### `app.py`

Contains the main Streamlit application, including the dashboard, student registration, teacher registration, grade management, and details pages.

### `main.py`

Contains the additional project code / application entry point.

### `school_data.json`

Stores student, teacher, and grade information locally.

### `README.md`

Project documentation.

## 🖥️ Application Sections

### 📊 Dashboard

The dashboard displays:

- Total number of students
- Total number of teachers
- Number of grades recorded
- Overall school average
- Recent students
- Faculty information

### 👨‍🎓 Register Student

Students can be registered using:

- Full Name
- Email
- Age
- Roll Number

The application checks for missing information, validates the email, and prevents duplicate roll numbers.

### 👨‍🏫 Register Teacher

Teachers can be registered using:

- Full Name
- Email
- Age
- Subject
- Employee ID

Duplicate employee IDs are prevented.

### 📚 Add Grade

Grades can be added by selecting a student and entering:

- Subject
- Marks

Marks are stored in the student's record and used to calculate the average score.

### 👤 Student Details

The application displays:

- Student name
- Roll number
- Age
- Email
- Average score
- Individual subject grades

### 👨‍🏫 Teacher Details

The application displays:

- Teacher name
- Employee ID
- Age
- Subject
- Email

## 💾 Data Storage

The application uses `school_data.json` as a local data store.

The data is organized into two main sections:

```json
{
    "students": [],
    "teachers": []
}
```

Student grades are stored inside each student's record.

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### 2. Open the project folder

```bash
cd ManagementApp
```

### 3. Install Streamlit

```bash
pip install streamlit
```

### 4. Run the application

```bash
streamlit run app.py
```

The Streamlit application will open in your browser.

## 🧠 Concepts Practiced

This project helped me apply:

- Python fundamentals
- Functions
- Lists and dictionaries
- File handling
- JSON
- Classes and objects
- Inheritance
- Abstraction
- Abstract Base Classes
- Static methods
- Data validation
- Streamlit
- Basic UI design
- Git and GitHub

## 🎯 Project Goal

The main goal of this project was to move from **learning Python concepts to building a working application**.

Instead of only practicing individual programs, I used Python concepts to create a functional school management system with a web-based interface.

## 🔮 Future Improvements

Possible future improvements include:

- 🔐 Student and teacher login system
- ✏️ Edit and delete records
- 🗄️ SQLite / MySQL database
- 📊 Advanced performance analytics
- 📱 Responsive UI improvements
- 📄 Generate student report cards
- 🔔 Notifications and announcements
- 👥 Role-based access
- 🌐 Deployment as an online application

## 👨‍💻 Author

**Virat Ketan Patil**

B.Tech CSE (AI & ML)

This is my first Python project and one of the projects in my journey toward becoming an **AI/ML Engineer**.

---

⭐ **If you like the project, consider giving the repository a star!**
