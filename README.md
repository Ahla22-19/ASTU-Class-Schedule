# ASTU Class Schedule Viewer

A C++ console application for viewing freshman class schedules at Adama Science and Technology University (2016 academic year).

---

📌 Overview

This program allows students to quickly access their weekly class schedules by selecting their school and section. It serves as a simple, offline alternative to checking timetables manually.

Supported Schools:

· 🏛️ Pre-Engineering — Sections 1–42
· 🔬 Applied Science — Sections 1–14

---

✨ Features

· Interactive school and section selection
· Formatted table display for each section
· Input validation for section ranges
· Developer credits display
· Lightweight and runs entirely in the terminal

---

🛠️ Requirements

· C++ compiler (supports C++98 or later)
· Terminal / Command Prompt

---

🚀 Compilation & Execution

Compile:

```bash
g++ astu_schedule.cpp -o astu_schedule
```

Run:

```bash
./astu_schedule
```

Windows (MinGW):

```bash
g++ astu_schedule.cpp -o astu_schedule.exe
astu_schedule.exe
```

---

📖 How to Use

1. Launch the program.
2. Enter 1 for Pre-Engineering or 2 for Applied Science.
3. Enter your section number when prompted.
4. Your schedule will be displayed in a table.
5. Developer credits appear at the bottom.

---

🧪 Example

```
********************************************************************
     Welcome to ASTU 2016 Fresh Man Schedule   
            Please select School 

**   FOR PRE     Enter      1   
**   FOR APPLIED Enter      2  
> 1

  Welcome to Pre-Enginering School  
  Enter Section Number (1–42)
> 1

 SECTION 1 Schedule
--------------------------------------------------------------------
| COURSE TITLE     | CODE     | DAYS  | TIME            | ROOM     |
| Applied Math II  | Math1102 | TH&F  | 2:00–4:00, 8–10 | B522R1   |
...
```

---

👥 Developers

· Afomiya Tedla
· Ahilam Zeynu
· Meklit Abeje
· Sara D.
· Rahawa Getachewu

---

📄 License

This project is for educational purposes and was created as part of a university programming assignment.

---

📬 Contact

For questions or contributions, please reach out to any of the developers listed above.

---

© 2016 – Adama Science and Technology University
