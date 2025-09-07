Webknot Assignment

This project is a full-stack application that demonstrates event management features such as student attendance, popularity analysis, and feedback tracking. It includes a Node.js backend, SQL database setup, and visualization screenshots.

📂 Project Structure
├── server.js               # Node.js backend server
├── package.json            # Project dependencies
├── db_init.sql             # Database schema initialization
├── queries.sql             # SQL queries for reports
├── events.db               # SQLite database file
├── ui_mockup.html          # UI mockup (frontend prototype)
├── screenshots/            # Result screenshots (charts & reports)
│   ├── popularity.png
│   ├── attendance.png
│   ├── feedback.png
│   └── top_students.png
├── reports.md              # Analysis & findings
├── design_doc.md           # System design documentation
└── ai_conversation_log.txt # Development discussion log

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/yourusername/webknot-assignment.git
cd webknot-assignment

2. Install Dependencies
npm install

3. Initialize Database

Run the SQL schema and queries:

sqlite3 events.db < db_init.sql
sqlite3 events.db < queries.sql

4. Start the Server
node server.js


The app will run on http://localhost:3000
 (or the port configured in server.js).

📊 Features

Student event attendance tracking

Popularity analysis by event

Feedback collection and reporting

Top-performing students analytics

Mockup UI (ui_mockup.html)

Pre-generated result screenshots

🖼️ Screenshots
Popularity	Attendance	Feedback	Top Students

	
	
	
📄 Documentation

design_doc.md
 – System design and architecture

reports.md
 – Report analysis and findings

⚙️ Tech Stack

Backend: Node.js, Express

Database: SQLite

Frontend: HTML Mockup

Visualization: SQL queries + charts

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License.
