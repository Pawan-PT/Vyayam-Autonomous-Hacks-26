# Vyayam-Autonomous-Hacks-26
AI-assisted physiotherapy tool to correct posture and basic movements for students. Built for Autonomous Hacks 26.
# Vyayam — AI Physiotherapy Prototype

This repository contains the early working MVP for **Vyayam**, an AI-assisted physiotherapy system that helps detect movement issues and guides users with safe, corrective exercises.

### 🩺 What this MVP can already do
✔ Basic posture & movement detection  
✔ Real-time exercise form validation using keypoints  
✔ Physio-style instructions (squats, neck & knee routines)  
✔ Basic diagnosis info with confidence %  
✔ Auto-generated physiotherapy progress reports (PDF)  
✔ Early prototype of red-flag screening (safety checks)

### 📌 How it works (Prototype Reality)
- Uses pose estimation to track movement angles
- Compares form to physiotherapy guidelines
- Gives corrective feedback (example: “Legs uneven — fix now”)
- Generates a PDF progress summary after exercise attempts

### 🚧 Current Status
This is not a medical replacement. It only provides:
- Early posture correction
- Simple exercise guidance
- Basic safety advice

### 🎯 Built for
**Autonomous Hacks 26 — GDG Gandhinagar**  
(Phase 1 Submission: MVP + Research)

### 📷 Screenshots
See `/screenshots` folder for:
- Welcome & workflow
- Diagnosis with reasoning
- Exercise instructions
- Real-time posture correction
- Progress report generation

### 🛠 Tech Stack
- **Python** — main development language
- **MediaPipe / OpenCV** — pose & keypoint detection for movement form
- **Streamlit** — UI for assessment, exercises, posture feedback, and report view
- **ReportLab / Python-PDF** — generating physiotherapy PDF reports
- **Custom Physiotherapy Rules** — safety & exercise logic from physio knowledge (not generic AI)

---

More updates will be added during the hackathon build phase.
