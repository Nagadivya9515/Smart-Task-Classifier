# 🧠 Smart Task Classifier

A simple web app that uses Hugging Face's zero-shot classification model automatically categorizes your tasks based on user-defined labels.

> Built with HTML, CSS, and JavaScript – no backend required!

---

## 🚀 Features

- 🏷 Define your own custom task categories
- ⚡ Auto-classify tasks using AI (Facebook's `bart-large-mnli`)
- 💾 Save categories and task history to localStorage
- 📁 Export categorized tasks to a `.txt` report
- 🔊 Sound feedback after classification
- 📱 Responsive and mobile-friendly UI

---

## 🛠 How It Works

1. Add your categories (e.g., `Coding: development work`, `Writing: content creation`).
2. Enter a list of tasks.
3. Click "Classify Tasks" – the app will:
   - Send each task to Hugging Face's NLI model
   - Get the best-matching category for each
4. View results in a table with confidence scores
5. Export if needed!

---

## 🔧 Use Cases

Here are a few scenarios where Smart Task Classifier shines:

### 🧑‍🎓 Student Productivity
- Classify academic vs. personal vs. project tasks
- Prioritize assignments based on task type (e.g., "Reading", "Coding", "Submissions")

### 💼 Project Management
- Auto-categorize tasks into `Frontend`, `Backend`, `Testing`, etc.
- Help team leads sort tasks before assigning them

### ✍️ Content Planning
- Organize task ideas into `SEO`, `Social Media`, `Writing`, `Design`

### 🛠 Freelance Work Tracking
- Separate tasks by client or task type (`Client A`, `Client B`, `Admin Work`)

### 📚 Learning Journals
- Classify study to-dos like `Practice`, `Tutorial`, `Reading`, `Projects`

### 👩‍💻 Developer Sprint Planning
- Tag dev tasks into `Bug Fixes`, `Feature Requests`, `Code Review`, etc.

### 🎯 Goal Tracking
- Group goals into `Health`, `Finance`, `Habits`, `Learning`, etc.

---

## 🧪 Demo

[Live Demo](#) — (https://nagadivya9515.github.io/Smart-Task-Classifier/)

---

## 🧰 Tech Stack

- HTML5 + CSS3
- JavaScript (Vanilla)
- Hugging Face Inference API (`facebook/bart-large-mnli`)

---
## 📄 License

MIT License

---

## 💡 Author

Made with 💚 by [Nagadivya](https://github.com/Nagadivya9515)
