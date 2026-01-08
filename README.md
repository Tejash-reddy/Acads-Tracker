# I was too lazy to write readme so i used ai to generate it#
🎓 Student Dashboard

A student-centric academic dashboard that helps manage courses, CGPA/SGPA calculation, and timetable generation from structured JSON data.
Built to simplify semester planning, course selection, and academic tracking in one place.

✨ Features
📊 CGPA & SGPA Calculator

Add/remove courses dynamically

Select grades per course

Automatic SGPA per semester

Overall CGPA calculation

Credit-weighted grading system

🗓️ Timetable Generator

Auto-generates timetable from selected courses & sections

Supports Lecture (L), Tutorial (T), Practical (P)

Time slots mapped from 8:00 AM – 7:00 PM

Handles:

Multiple sections per course

Multiple schedules per section

Multi-hour practical slots

Day & slot inheritance

📚 Course Management via JSON

Courses, credits, and schedules are loaded from JSON files

Easy to update without touching UI logic

Normalized slot handling (e.g. 12 → [1,2])

🎯 Branch & Semester Logic

Branch selection (A / B series support)

Dual-degree handling

Semester-specific course selection

Global semester state

🧱 Tech Stack

Frontend: HTML, CSS, JavaScript

State Management: LocalStorage

Data Format: JSON

Backend: Optional (works fully offline without auth)
