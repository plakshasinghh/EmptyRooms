# EmptyRoom



**EmptyRoom** is a full-stack web application built to solve the **classroom and lab availability problem** at our university. It helps students and professors find and book free lecture halls in real-time, using a backend system that automatically extracts and syncs data from the official timetable Excel sheets.

---

## Key Features

- 🏫 **Live Classroom Availability** – Easily find which rooms are free at a given time.
- 🗓️ **Automated Timetable Parsing** – A Python script parses Excel schedules and updates the MongoDB database autonomously.
- 📊 **Supports 500+ Users** – Used by both students and faculty for booking lecture halls and labs.
- 🔗 **REST API Tested via Postman** – Ensured stability before deployment.
- 🖥️ **Intuitive UI** – Built using EJS templates, HTML/CSS, and JavaScript.

##  How It Works

1. University provides Excel timetable.
2. Python script parses the data using **Pandas** and **NumPy**.
3. Script updates the **MongoDB** database using **PyMongo**.
4. Web app (built with Node.js & Express) fetches room data and shows availability.
5. Users can view or book rooms for extra sessions, club activities, or surprise tests.

---

##  Impact

> Helped reduce double-booking and classroom conflicts  
>  Actively used by over **500 students and faculty members**  
>  Saved time and manual effort through automation



