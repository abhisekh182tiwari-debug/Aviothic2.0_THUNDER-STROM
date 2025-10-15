# 🧠 Smart Student Scheduler

The *Smart Student Scheduler* is a simple and efficient web-based system designed to help students register and organize academic information easily.  
It collects basic details such as *Gmail, **Name, **Branch, and **CGPA*, and then processes this information to provide scheduling or academic insights.

---

## 🚀 Features

- 📨 Login using Gmail  
- 🧾 Input Student Details: Name, Branch, and CGPA  
- 📅 Automatically organizes or schedules tasks  
- 🧠 Smart recommendation system (based on CGPA and branch)  
- 📊 Simple flowchart visualization of student input process  

---

## 🧩 Workflow

1. *Start*
2. *Enter Gmail*
3. *Enter Student Name*
4. *Enter Branch*
5. *Enter CGPA*
6. *Validate Input Data*
7. *Save/Display Student Information*
8. *End*

---

## 📜 Example Input

| Field  | Example |
|--------|----------|
| Gmail  | student123@gmail.com |
| Name   | Abuzar Iqbal |
| Branch | Computer Science |
| CGPA   | 8.6 |

---

## 🖼 Flowchart

```mermaid
flowchart TD
    A([Start]) --> B[Enter Gmail]
    B --> C[Enter Name]
    C --> D[Enter Branch]
    D --> E[Enter CGPA]
    E --> F{Valid Data?}
    F -- Yes --> G[Save Student Details]
    F -- No --> B
    G --> H[Display Success Message]
    H --> I([End])
