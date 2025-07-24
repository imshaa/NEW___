# 🗓️ University Timetable Management System

A web-based timetable management system built using **Django** (Python) and front-end technologies like **HTML**, **CSS**, and **JavaScript**. This system allows automated scheduling of classes, rooms, faculty, and departments, streamlining the process of creating and managing academic timetables.

---

## 🚀 Features

* User authentication (Login/Register)
* Add/edit/delete:

  * Departments
  * Teachers
  * Courses
  * Classrooms
* Automatic timetable generation
* Conflict checking (room, teacher, time)
* Responsive frontend using HTML, CSS & JS
* Admin dashboard to manage schedules
* Timetable view by department/teacher/classroom

---

## 🛠 Tech Stack

| Technology           | Purpose                                                       |
| -------------------- | ------------------------------------------------------------- |
| Django               | Backend framework & database models                           |
| SQLite               | Default Django database (can be upgraded to PostgreSQL/MySQL) |
| HTML/CSS             | Frontend design & layout                                      |
| JavaScript           | UI interactivity                                              |
| Bootstrap (optional) | Styling and layout enhancements                               |

---

## 🔧 Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/timetable-system.git
   cd timetable-system
   ```

2. **Create a virtual environment**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the server**

   ```bash
   python manage.py runserver
   ```

6. **Visit the app**

   Open your browser and go to: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 📁 Project Structure

```
timetable-system/
├── home/                 # Django app
│   ├── templates/        # HTML templates
│   ├── static/           # CSS, JS, images
│   ├── views.py          # Views for rendering logic
│   ├── models.py         # Database models
│   └── urls.py           # App-specific URLs
├── timetable_system/     # Project settings
│   └── settings.py       # Django settings
├── db.sqlite3            # Database
├── manage.py             # Django command-line utility
└── requirements.txt      # Python dependencies
```

---

## 💡 Future Improvements

* AI-assisted timetable generation using constraints
* Student-side view for personal schedules
* Export to PDF
* Notification system for schedule changes
* Mobile-first UI redesign

---

## 🤝 Contributing

Feel free to fork this repo and submit pull requests. For major changes, please open an issue first.




