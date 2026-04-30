# fent.

> A minimalist study tracker for JEE 2027 . This tool is vibecoded for a clean look and built for personal use to maintain track of study.
---

## Intent

 This is a personal project used to track every chapter in the JEE syllabus  over a 7 month period from **April  to November**. It is built for a drop year students. There are no social features or any distractions.

---

## Functional Components

### 1. The Weekly Window
<p align="center">
  <img width="100%" alt="Weekly View" src="https://github.com/user-attachments/assets/3612ea0c-4260-4f1f-9ae9-67eec0b49f8c" />
</p>

The dashboard is designed to limit your focus to the current seven days. Looking at the entire syllabus at once can be overwhelming, so this view isolates only the chapters you need to work on right now. It shows the subject tags, how many tasks you have finished, and a progress bar that gives a neutral look at your weekly output.

### 2. Syllabus Management
<p align="center">
  <img width="100%" alt="Subject List" src="https://github.com/user-attachments/assets/1c9a5c92-ebc1-4773-a754-3f59fe58cc48" />
</p>

The subject lists contain every chapter in the JEE syllabus. To ensure the study quality is high, a chapter is not considered "done" until four specific steps are checked off:
*   **Theory**: Reading the concepts and making notes.
*   **Module**: Solving the standard practice questions from your material.
*   **PYQ**: Finishing the previous year questions to see the actual exam level.
*   **Revision**: A final review to make sure the information sticks.

### 3. Analytics and Performance
<p align="center">
  <img width="100%" alt="Analytics" src="https://github.com/user-attachments/assets/7633fe9a-cdda-4581-9d5a-cd30262eab12" />
</p>

The analytics section provides a factual summary of your progress. Ring charts display the completion percentage for each subject. It also tracks your performance in mock tests by recording your scores for both Mains and Advanced formats. This helps you see if you are actually improving or just staying at the same level.

### 4. Activity Heatmap
<p align="center">
  <img width="100%" alt="Heatmap" src="https://github.com/user-attachments/assets/3e7ea00a-c1b0-45da-a2c5-585493cb27c7" />
</p>

This is a visual record of your work over time. Similar to a GitHub contribution graph, each box represents a day. The color gets darker based on how many tasks you completed on that specific date. Since it logs activity when you actually tick a task, it serves as an honest history of your consistency.

### 5. Backlog Tracking
<p align="center">
  <img width="100%" alt="Backlog" src="https://github.com/user-attachments/assets/a55e6950-7b69-42cc-b47e-59a1e40e0779" />
</p>

If a chapter passes its deadline and is not finished, it moves to the backlog. The system tracks exactly how many days late you are and sets your status to "On track," "Slightly behind," or "Danger zone". It is a simple way to see exactly how much work you need to catch up on.

---

## Test Schedule

The tracker follows a high testing frequency that i made for myself which is as follows-
| Format | Frequency | Max Score |
| :--- | :--- | :--- |
| **JEE Mains** | 3 per month | 300 Marks |
| **JEE Advanced** | 1 per month | 360 Marks |

---

## Technical Specs

*   **Live App**: [fent-nu.vercel.app](https://fent-nu.vercel.app/)
*   **Privacy**: All data is stored locally in your browser. No data is sent to a server, and no account is required.
*   **UI**: Minimalist, OLED-optimized dark mode to reduce eye strain during long hours.
*   **Customization**: The syllabus and dates are stored in data arrays (`MATH`, `CHEM`, `PHYS`) in the source code for easy editing.

---

