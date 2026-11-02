# EX. 04 - SLOT TIME TABLE

**Course Code:** 19AI414  
**Course Title:** Fundamentals of Web Application Development  
**Department:** Artificial Intelligence and Data Science  
**Institution:** Saveetha Engineering College (Autonomous)  

---

## 🎯 AIM
To develop a responsive website to display the Semester Slot Timetable using HTML and CSS.

---

## 🛠️ ALGORITHM

1. **Initialize Project:** Create a project directory or Django static/template structure.
2. **HTML Structure:**
   - Define semantic HTML elements (`<header>`, `<div class="container">`, `<table>`, `<footer>`).
   - Add college name and department headers.
   - Add a student identification banner (Name, Register Number, Reference Number).
3. **Primary Timetable Matrix:**
   - Build a 2-level table header (`<thead>`) displaying the day and period timings (08:30 AM to 04:15 PM).
   - Use `rowspan` to create continuous columns for **TEA BREAK** (between 10:30 - 10:50) and **LUNCH BREAK** (between 12:50 - 01:40) across all week rows (Monday to Saturday).
   - Use `colspan` to merge multi-hour slots for practical laboratory sessions (e.g., Web App Lab, DBMS Lab, Python Lab).
4. **Course Reference Table:**
   - Create a secondary table listing **S.No**, **Course Code**, and **Course Title** for all enrolled subjects.
5. **CSS Styling:**
   - Apply clean table borders, alternating row colors (`nth-child`), and hover states.
   - Use institutional blue tones (`#003366`) and distinct colors for lab blocks and break intervals.
6. **Execution & Verification:**
   - Open `timetable.html` in a web browser or execute via Django (`python manage.py runserver`).
   - Verify layout alignment, borders, and responsiveness.

---

## 💻 CODE REPOSITORY

The complete code is available in [timetable.html](file:///C:/Users/acer/.gemini/antigravity/scratch/slot-time-table/timetable.html).

---

## 📸 HOW TO RUN & VIEW OUTPUT

1. **Directly in Browser:**
   - Double-click `timetable.html` or open it with Google Chrome / Microsoft Edge.
2. **Via Django (Optional for Lab Submission):**
   - Place `timetable.html` inside your Django app's `templates/` folder.
   - Map a path in `urls.py` and run `python manage.py runserver`.

---

## 🏆 RESULT
Thus, the website to display the semester slot timetable has been successfully developed and executed using HTML and CSS.
