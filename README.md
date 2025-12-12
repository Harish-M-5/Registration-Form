# Registration-Form
 Simple registration form that saves student details and shows them in a list 

 ---
 ## 📌 Introduction

This project is a Complete Student Registration System built using HTML, CSS and  JavaScript.
It includes two pages in one file:
1️⃣ Registration Form
2️⃣ Registered Students List (with Delete option)

No backend needed — data is stored in localStorage
---.
## 📌 Explanation

- User enters details like Name, Age, Gender, Course, Email, Password.

- JavaScript performs real-time validation and shows error messages.

- On successful form submission, details are stored locally.

- The second page displays the list of registered students, with Delete functionality.

- Tabs switch between Registration ↔ Registered List using pure JavaScript.

## 📌 Features

- Two-page navigation inside one file

- Real-time validation

- Required fields & error messages

- Password validation

- Save data in localStorage

- Display students in table

- Delete a student

- Responsive layout 

---

## 📌 Technologies Used

- HTML5 – Page structure

- CSS3 – UI styling, layout, shading

- JavaScript (ES6) – Validation, storage, page switching

- localStorage – Save student records

## 📌 Code Explanation
- HTML

<nav> → Two tabs: Registration & Registered List

<section> → Each page wrapped separately

<form> → Input fields (Name, Age, Gender, Course, Email, Password)

<table> → Displays registered students

- CSS

Custom variables (--card-bg, --page-bg, etc.) for theme

.card → White box with shadow

.tab.active → Highlight active page

.row, .col-1, .col-2 → Responsive form layout

.error → Inline error message

- JavaScript

showPage() → Switch tabs

validateAll() → Validates every input (live validation)

localStorage → Save & retrieve student list

renderTable() → Convert stored data → table rows

escapeHtml() → Prevents script injection

delete button → Removes specific student

form.reset() → Clears form after submit

---

## 🎥Demo Video

https://github.com/user-attachments/assets/3dac8fef-b91b-40fc-b4b3-09cc7f7e89e2


----
## Output
<img width="1920" height="1080" alt="Screenshot 2025-12-12 185156" src="https://github.com/user-attachments/assets/4de8c1a3-d5c9-4002-8430-cfe3100e400d" />

<img width="1920" height="1080" alt="Screenshot 2025-12-12 185222" src="https://github.com/user-attachments/assets/f8474e21-cf20-4ecf-97ae-f3a620b90577" />

<img width="1920" height="1080" alt="Screenshot 2025-12-12 185333" src="https://github.com/user-attachments/assets/1658de0f-dbfc-454d-8bd9-9456c1fdb98f" />

----
## 📌 License

This project is released under the MIT License  free to use and modif


This project is released under the MIT License — free to use and modify.
