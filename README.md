# Computer Science — Senior Year (Level 4, Semester 1)
### Faculty of Computers and Information — Suez Canal University (2026–2027)

---

## Weekly Timetable

| Day | 09:00 AM – 11:00 AM | 11:00 AM – 01:00 PM | 01:00 PM – 03:00 PM | 03:00 PM – 05:00 PM |
|:---:|:---:|:---:|:---:|:---:|
| **الأحد**<br>*(Sunday)* | **Sec 1:** Data Mining *(Lab 10A)*<br>**Sec 2:** Dynamic Languages *(Lab 2A)*<br>**Sec 3:** Distributed Systems *(Lab 5A)* |  **Data Mining**<br>*أ.د. أسامة فاروق*<br>*(Hall 2A)* | **Sec 1:** Distributed Systems *(Lab 5A)*<br>**Sec 2:** Data Mining *(Room 3A)*<br>**Sec 3:** Dynamic Languages *(Lab 10A)* | **Sec 1:** Dynamic Languages *(Lab 9A)* |
| **الإثنين**<br>*(Monday)* |  **Dynamic Languages**<br>*د. سماح ذكريا*<br>*(Hall 3B)* | **Sec 1:** Computer Vision *(Lab 1A)*<br>**Sec 2:** Mobile Comm System *(Lab 4A)*<br>**Sec 3:** Data Mining *(Lab 6A)* | *(Student Activities)* | **Sec 1:** Computer Vision *(Lab 1A)*<br>**Sec 2:** Mobile Comm System *(Lab 6A)*<br>**Sec 3:** Mobile Comm System *(Lab 3B)* |
| **الثلاثاء**<br>*(Tuesday)* | **Mobile Communication System**<br>*أ.د. حسن المهدي*<br>*(Hall 1A)* | **Computer Vision System**<br>*أ.م.د. محمد ميعاد*<br>*(Room 5B)* | **Distributed Systems**<br>*د. جهاد طاهر*<br>*(Hall 1B)* | **Sec 1:** Mobile Comm System *(Lab 3B)*<br>**Sec 2:** Distributed Systems *(Lab 5B)*<br>**Sec 3:** Computer Vision *(Lab 1A)* |


---

## Registered Courses Directory

| Course | Lecturer | Teaching Assistant (TA) | Lecture Slot | Quick Link |
|---|---|---|:---:|:---:|
| **Data Mining** *(تنقيب البيانات)* | أ.د. أسامة فاروق | م.م. سارة منجي | Sun 11:00 AM – 01:00 PM (Hall 2A) | [Open Folder](./Data%20Mining/) |
| **Dynamic Languages** *(اللغات الديناميكية)* | د. سماح ذكريا | م. محمد عبدالله | Mon 09:00 AM – 11:00 AM (Hall 3B) | [Open Folder](./Dynamic%20Languages/) |
| **Mobile Communication System** *(نظم الاتصالات المتنقلة)* | أ.د. حسن المهدي | م. ميريهان هشام | Tue 09:00 AM – 11:00 AM (Hall 1A) | [Open Folder](./Mobile%20Communication%20System/) |
| **Computer Vision** *(نظم رؤية الحاسب)* | أ.م.د. محمد ميعاد | م. فاطمة السيد | Tue 11:00 AM – 01:00 PM (Room 5B) | [Open Folder](./Computer%20Vision/) |
| **Distributed Systems** *(النظم الموزعة)* | د. جهاد طاهر | م.م. هبة الرحمن | Tue 01:00 PM – 03:00 PM (Hall 1B) | [Open Folder](./Distributed%20Systems/) |


---

## Repository Structure

Every course is uniformly organized into standard subdirectories to keep original university PDFs separate from generated explanations and notes:

```text
Year4_Semester1_CS/
├── README.md                                  # Repository overview and weekly schedule
├── .gitignore                                 # Git configuration
│
├── Computer Vision/
│   ├── README.md                              # Lecture & section index log
│   ├── Lectures/
│   │   ├── PDFs/                              # Slide decks & lecture handouts (.pdf)
│   │   └── Explanations/                      # Markdown notes & deep-dive explanations
│   └── Sections/
│       ├── PDFs/                              # Section sheets & assignments (.pdf)
│       └── Explanations/                      # Lab solutions & walk-throughs
│
├── Data Mining/
│   ├── README.md
│   ├── Lectures/
│   │   ├── PDFs/
│   │   └── Explanations/
│   └── Sections/
│       ├── PDFs/
│       └── Explanations/
│
├── Distributed Systems/
│   ├── README.md
│   ├── Lectures/
│   │   ├── PDFs/
│   │   └── Explanations/
│   └── Sections/
│       ├── PDFs/
│       └── Explanations/
│
├── Dynamic Languages/
│   ├── README.md
│   ├── Lectures/
│   │   ├── PDFs/
│   │   └── Explanations/
│   └── Sections/
│       ├── PDFs/
│       └── Explanations/
│
└── Mobile Communication System/
    ├── README.md
    ├── Lectures/
    │   ├── PDFs/
    │   │   └── Lecture_1.pdf                  
    │   └── Explanations/
    └── Sections/
        ├── PDFs/
        └── Explanations/
```

---

## How to Add New Lectures & Request Explanations

1. **Upload the PDF:**
   - For a lecture: Place the file in `[Course Name]/Lectures/PDFs/` (e.g. `Lecture_2.pdf`).
   - For a section/lab: Place the file in `[Course Name]/Sections/PDFs/` (e.g. `Section_1.pdf`).
2. **Prompt the Assistant:**
   - Message the AI:
     > *"I added Lecture X to [Course Name]. Please review the PDF, create a comprehensive explanation with summaries, key concepts and at least 100 MCQ questions, in this repo, and update the course README log."*
3. **Automatic Documentation:**
   - The assistant will extract and explain the material in `[Course Name]/Lectures/Explanations/Lecture_X_Explanation.md` and link it directly in the course's tracking table.
