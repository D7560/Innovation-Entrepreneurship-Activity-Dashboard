# Innovation & Entrepreneurship Activity Dashboard

This is a simple web-based dashboard project built with **HTML, CSS, JavaScript, Bootstrap, and Chart.js**.  
It helps track activities related to Innovation & Entrepreneurship (I&E), such as workshops, pitches, demos, and mentorship events.

---

## 📂 Project Structure

```
ie-activity-dashboard/
├─ index.html        # Main HTML file
├─ css/
│  └─ styles.css     # Custom styles
├─ js/
│  └─ app.js         # JavaScript logic
└─ README.md         # Instructions
```

---

## 🚀 Features
- Add, edit, and delete activities.
- Data persistence using **localStorage**.
- KPI cards showing **total activities, participants, average impact, and upcoming events**.
- **Charts** using Chart.js:
  - Line chart: Activities over time (monthly)
  - Pie chart: Activities by type
- Search box for filtering activities.
- Export data as CSV file.
- Clear all data button (resets dashboard).

---

## ▶️ How to Run

1. Unzip the project.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox).
3. The dashboard will load with sample data.

---

## ⚙️ Dependencies
- [Bootstrap 5](https://getbootstrap.com/) (via CDN)
- [Chart.js](https://www.chartjs.org/) (via CDN)

Both are included via CDN in `index.html`, so no installation is required.

---

## 📊 Usage
- Click **+ Add Activity** to add a new event.
- Use **Edit** and **Delete** buttons in the table to manage activities.
- Use the **Search** box to quickly find an activity.
- Click **Export CSV** to download your data.
- Click **Clear All** to reset everything.

---

## 📝 Notes
- Data is stored locally in your browser (localStorage). Closing the browser won’t delete your data unless you clear it manually.
- Works entirely offline once loaded.

---

## 💡 Future Enhancements
- Cloud storage (Firebase or MongoDB)
- Authentication (Admin / Student / Mentor roles)
- More advanced chart filters and reports
