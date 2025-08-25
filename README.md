# Tick_it
A simple One-Day To-Do List Web App designed to keep your focus on what matters today. This project demonstrates task management with a basic database integration.


⚙️ Project Setup (npm)

Write This Commands in terminal for setup:
npm init -y

npm i express

npm i pg

node index.js (run the file)

🗄️ Database Setup

Create a database (MySQL / Postgres depending on your stack).

Define a table/collection for tasks with fields such as:

id (primary key)

title (task description)

Update your database connection string in the project config file.

Example (pgadmin):

CREATE TABLE tasks (
  id INT AUTO_INCREMENT PRIMARY KEY,
  title VARCHAR(255) NOT NULL
);

➕ Creating New Items

Navigate to the input box on the home page.

Enter a task name and click Add.

✏️ Updating Items

Click the edit icon next to any task.

Update the task name or mark it as completed.

Changes will be reflected in the database immediately.

❌ Deleting Items

Click the delete icon next to any task.

The task will be removed from both the UI and the database.

🚀 Opportunities for Enhancement

Authentication: Add login/signup to save tasks per user.

Due Dates & Reminders: Allow tasks to have deadlines.

Categories/Tags: Group tasks by subject or priority.

Dark Mode: Improve UI with a theme toggle.

API Integration: Create REST APIs for mobile app compatibility.

⚡ This project is built for productivity — focus on one day at a time!
