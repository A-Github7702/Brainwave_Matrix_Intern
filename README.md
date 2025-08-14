# Brainwave_Matrix_Intern
About voice day planner

## 📅 Day Planner with Voice Commannd

**Overview**

This **Day Planner Web App** helps you organize your daily schedule with **color-coded hourly slots**, **motivational images**, and **voice command support**.
It’s built with **pure HTML, CSS, and JavaScript** — no external frameworks — so you can just open the HTML file in your browser and start using it instantly.

 **Features**

✅ **Hourly Planner (12 AM – 11 PM)** — All 24 hours are displayed with **bright, distinct background colors** for easy identification.
✅ **Add Tasks by Clicking** — Click any time slot to add or edit a task.
✅ **Voice Command Input** — Use your microphone to add tasks by speaking.
✅ **Task Status Toggle** — Click on a task to toggle between **In Progress** and **Completed**.
✅ **Progress Tracking Dashboard** — Displays total tasks, number completed, in progress, and overall completion percentage.
✅ **Daily Motivation** — Displays a new motivational image and quote every day.
✅ **Offline-Friendly Images** — Uses stable image sources with fallback support.
✅ **Instant Setup** — Just open the HTML file in any modern browser.

 **How It Works**

1. **Time Slots**

   * Generated dynamically using JavaScript.
   * Each slot gets a **unique background color** from a predefined vibrant palette.
   * Clicking on a slot prompts you to enter a task.

2. **Task Management**

   * Tasks are stored in memory while the page is open.
   * Each task has a **status**: `"in progress"` or `"completed"`.
   * Clicking a task toggles its status and updates the stats.

3. **Voice Commands**

   * Uses the **Web Speech API** to capture spoken input.
   * After speaking, the app asks which time slot to assign the task to.

4. **Motivational Images**

   * Rotates through a **set of predefined images** based on the day of the month.
   * If an image fails to load, a fallback placeholder is shown.

5. **Progress Stats**

   * Updates dynamically whenever a task is added or status changes.
   * Shows totals and percentage completion.

**How to Use**

1. Download or clone the repository.
2. Open `day-planner.html` in your browser.
3. **Add tasks** by clicking on any slot or using the microphone button.
4. **Toggle status** by clicking on an existing task.
5. Enjoy **daily motivational quotes** while tracking your progress.

 **Tech Stack**

* **HTML5** — Structure and layout
* **CSS3** — Styling and color themes
* **JavaScript (ES6)** — Logic, task management, and voice commands
* **Web Speech API** — Voice input
* **Picsum Photos** — Daily motivational images

 **Future Improvements**

* Save tasks in **LocalStorage** so they persist after refreshing the page.
* Add drag-and-drop to reschedule tasks.
* Allow recurring daily tasks.
* Integrate push notifications for task reminders.

