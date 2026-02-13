# 🎵 Mashup Generator Assignment Submission
**Name:** [Your Name]
**Roll Number:** [Your Roll Number]
**Group:** [Your Group]

## 📋 Project Overview
This repository serves as the submission hub for the Mashup Assignment. [cite_start]The project addresses the requirement to develop two distinct implementations for generating audio mashups: a Command Line Interface (Program 1) and a Web Service (Program 2)[cite: 6].

## 📂 Deliverables

### 1. [Program 1: CLI Implementation (Link)](LINK_TO_YOUR_CLI_REPO)
* [cite_start]**File:** `102103123.py` (Adheres to naming convention [cite: 15])
* **Features:** Command-line argument validation, local file generation.

### 2. [Program 2: Web Service (Link)](LINK_TO_YOUR_WEBAPP_REPO)
* **Live Link:** [https://mashup-x1jv.vercel.app/](https://mashup-x1jv.vercel.app/)
* [cite_start]**Features:** Email delivery, ZIP file format[cite: 39].

---

## 🧪 Result & Validation Table
[cite_start]The following test cases demonstrate compliance with the assignment constraints (N > 10, Y > 20)[cite: 18, 21].

| Test Case | Inputs | Expected Outcome | Actual Result |
| :--- | :--- | :--- | :--- |
| **Standard Run** | `("Sharry Maan", 20, 30)` | **Success:** ~10 min audio file created. | ✅ Pass |
| **Invalid Videos** | `("Artist", 5, 30)` | **Error:** "Number of videos must be > 10" | ✅ Pass |
| **Invalid Duration** | `("Artist", 20, 10)` | **Error:** "Duration must be > 20" | ✅ Pass |
| **Web Delivery** | `(Valid Inputs + Email)` | **Success:** ZIP file received in inbox. | ✅ Pass |

## 🔄 Project Flowchart


## 📄 Assignment Constraints Checklist
- [x] [cite_start]Program 1 file named `<RollNumber>.py` [cite: 15]
- [x] [cite_start]CLI checks for correct number of parameters [cite: 26]
- [x] [cite_start]Web App sends result in ZIP format [cite: 39]
- [x] [cite_start]Cuts first Y seconds from downloaded files [cite: 21]
