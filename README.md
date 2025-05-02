# REAL-TIME-CHAT-APPLICATION
A real-time messaging app built with Django, supporting user authentication, WebSocket-based instant messaging, and database integration.

🚀 Features
🔐 User login & registration

📡 Real-time messaging with WebSockets

💾 Messages stored in database

🧑‍💻 REST API for user/message management

🛠 Tech Stack
Backend: Django, Django REST Framework

Real-Time: Django Channels, WebSockets

Database: SQLite 


PROJECT STRUCTURE
chat-app/
│
├── chat/               # Chat logic (consumers, routing, models)
├── users/              # User authentication and profile management
├── chat_app/           # Main Django project settings
├── templates/          # HTML Templates (if any)
├── static/             # CSS, JS, etc.
├── db.sqlite3          # Default SQLite DB (can be changed)
├── manage.py           # Django CLI entry
└── requirements.txt    # Project dependencies
