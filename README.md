# Resume–Job Description Matcher & Feedback System 

## 📌 Project Overview

The **Resume–Job Description Matcher & Feedback System** is a console-based application developed in **C++** that compares a resume with a job description and provides a matching score along with basic feedback. The system uses text processing techniques to identify common skills and keywords between the resume and job description.

---

## 🎯 Objectives

* To read and process resume and job description text files
* To extract important keywords and skills
* To calculate a similarity or match score
* To provide feedback on missing or unmatched skills
* To improve understanding of C++ programming concepts

---

## 🛠️ Technologies Used

* **Programming Language:** C++
* **Concepts Used:**

  * File Handling
  * String Manipulation
  * STL (vectors, maps, sets)
  * Basic Algorithms
* **Compiler:** GCC / MinGW

---

## ⚙️ System Architecture

1. User provides resume and job description text files
2. Text data is read using file handling
3. Stop words are removed
4. Keywords are extracted
5. Matching logic is applied
6. Match score and feedback are displayed

---

## 🚀 Features

* Text file input support
* Keyword-based matching
* Match percentage calculation
* Identification of missing skills
* Simple console-based interface

---

## 📂 Project Structure

```
Resume-JD-Matcher/
│
├── resumes/
│   └── resume.txt
│
├── job_descriptions/
│   └── jd.txt
│
├── src/
│   ├── main.cpp
│   ├── matcher.cpp
│   └── matcher.h
│
├── README.md
└── Makefile (optional)
```

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Resume-JD-Matcher.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Resume-JD-Matcher
   ```

3. Compile the project:

   ```bash
   g++ src/main.cpp src/matcher.cpp -o matcher
   ```

4. Run the program:

   ```bash
   ./matcher
   ```

---

## 📊 Output

* Resume–JD match percentage
* List of matched skills
* List of missing skills
* Feedback for resume improvement

---

## 📜 Disclaimer

This project is developed purely for academic purposes and does not use advanced AI or ML techniques.
