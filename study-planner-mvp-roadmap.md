# Study Planner App – MVP Strategy & Roadmap

## 🎯 Target Audience
Competitive exam aspirants in India:  
- UPSC, SSC, NEET, GATE, Banking, etc.

## 💸 Business Model
- Rs. 99/month subscription (recurring, affordable)
- Goal: 5,000–10,000 paying users

---

## 🚀 MVP Feature Set (v1)

1. **Account Creation**
   - Email/phone login (Firebase Auth)
2. **Choose Exam & Target Date**
   - E.g., UPSC Prelims May 2026
3. **Study Time Input**
   - User selects available hours/day
4. **Smart Study Plan Generator**
   - Auto-generates plan from selected exam’s syllabus
5. **Daily Checklist & Tracker**
   - Tracks completion, keeps history
6. **Daily Reminder Notifications**
   - Firebase Cloud Messaging
7. **Progress Chart**
   - Visual progress tracker
8. **Premium Features**
   - Multiple plans per user
   - PDF export
   - Streak badges for consistency
   - AI-based daily tips

---

## 🛠️ Recommended Tech Stack

- **Frontend:** Kotlin + Jetpack Compose
- **Backend/DB:** Firebase (Firestore, Auth, Storage)
- **Notifications:** Firebase Cloud Messaging
- **Payments:** Razorpay
- **Analytics:** Firebase Analytics
- **(Optional) AI:** OpenAI API or rule-based logic

---

## 📆 Weeks 1–2: Planning & Setup

### 1. **Brainstorm & Name the App**
   - List 10+ naming options, shortlist top 3.  
   - Validate availability (.com, Play Store).

### 2. **Define Exam Templates**
   - Choose first 3 exams:
     - UPSC (Civil Services)
     - SSC (Staff Selection Commission)
     - NEET (Medical Entrance)
   - Break down each exam into paper/subject/modules.

### 3. **Design Basic UI Wireframes**
   - **Onboarding:** Login, exam selection, study time input
   - **Plan Generation:** Display generated plan, allow edits
   - **Checklist:** Today’s tasks, mark as complete
   - **Progress:** Progress chart, streaks, history

### 4. **Firebase Project Setup**
   - Create Firebase project
   - Enable Auth (email/phone)
   - Set up Firestore for user data
   - Enable Cloud Messaging
   - Set up Storage (for optional features)

### 5. **Task Tracking Board**
   - Create private board (Trello/Notion)
   - Columns: Backlog, To-Do, In Progress, QA, Done
   - Add tasks for each above milestone

---

## 🧩 Suggested Next Steps & Deliverables

| Week  | Goal                                   | Deliverable                               |
|-------|----------------------------------------|-------------------------------------------|
| 1     | Name, exam templates, wireframes       | Name shortlist, syllabus docs, UI sketches|
| 2     | Firebase setup, board setup            | Firebase project, Trello/Notion board     |
| 3–4   | Build onboarding, login, plan gen      | Basic app skeleton, plan gen prototype    |
| 5–6   | Checklist, notifications, tracking     | Checklist & reminder MVP                  |
| 7     | Progress chart, premium features (v1)  | Progress UI, stub premium options         |
| 8     | Payments, analytics, polish, QA        | Razorpay test, Firebase Analytics         |

---

## ✅ Quick Wins

- Use open-source syllabus data for exams (speed up plan gen)
- Leverage Firebase starter templates for Kotlin apps
- Keep UI minimal for MVP – focus on usability, not looks

---

## 📣 Tips

- Launch early to a small beta group for feedback
- Iterate on plan generation logic with real user data
- Focus on retention (notifications, streaks, value)

---

### Let me know if you want:
- Example wireframes (text or Figma)
- Sample Trello/Notion board template
- Firebase setup checklist
- Naming suggestions
- User stories or task breakdown

Happy building! 🚀