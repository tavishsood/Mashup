## 📋 Overview
This repository serves as the central hub for the **Mashup Generator** project. It is divided into two distinct implementations:

1.  **Program 1:** A standalone Command Line Interface (CLI) tool.
2.  **Program 2:** A full-stack Web Application with email delivery.

## 🔗 Project Deliverables

| Component | Repository Link | Description |
| :--- | :--- | :--- |
| **CLI Tool** | [**View Program 1 Code**](LINK_TO_CLI_REPO) | Python script (`<RollNumber>.py`) implementing the mashup logic locally. |
| **Web App** | [**View Program 2 Code**](LINK_TO_WEBAPP_REPO) | Next.js & Flask application hosted on Vercel. |

---

## ✅ Compliance Checklist
The following constraints from the assignment problem statement have been strictly implemented:

* **Constraint 1:** The CLI program accepts inputs strictly as command-line arguments. 
* **Constraint 2:** The number of videos ($N$) must be greater than 10. 
* **Constraint 3:** The trim duration ($Y$) must be greater than 20 seconds. 
* **Constraint 4:** The Web App delivers the final result as a **ZIP file** via email.

## 🧪 Methodology
Both implementations share a core processing pipeline:
1.  **Scrape:** Extract video URLs for the requested artist using `yt-dlp`.
2.  **Download:** Fetch audio streams directly (avoiding video overhead).
3.  **Process:** Use `FFmpeg` to trim the **first Y seconds** of each track.
4.  **Merge:** Concatenate the clips into a single continuous audio file.
5.  **Deliver:** Save to disk (CLI) or Zip & Email (Web App).
