#  Python Chat App

A real-time chat application built using **Flask**, **Socket.IO**, and **JavaScript** on the frontend. This project demonstrates how to build a simple, interactive chat system and deploy it for real-world use.


##  This Project Includes:

-  A Python virtual environment setup for isolated development  
-  Real-time messaging powered by **Flask** and **Socket.IO**  
-  An interactive frontend built with **HTML**, **CSS**, and **JavaScript**  
-  Server-side message handling and broadcasting logic  
-  Organized project structure with separate `static` and `templates` directories  
-  Local development server to test chat functionality  
-  Ready-to-deploy code for platforms like **Render**, **Replit**, or **Heroku**


##  Technologies Used

- **Python 3**
- **Flask**
- **Socket.IO**
- **JavaScript**
- **HTML & CSS**

##  Features

-  Real-time bi-directional communication using WebSockets
-  Join and chat with multiple users
-  Responsive web interface
-  Automatically scrolls to latest messages
-  Easy to deploy and extend

##  Requirements

- Python 3.7+
- pip (Python package installer)
- A modern web browser


  
##  Installation

1. **Clone the repository:**

```bash
git clone <your-repo-url>
cd <your-project-directory>
```

2. **Set up a virtual environment:**

```bash
# macOS/Linux
python3 -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Start the application:**

```bash
python app.py
```

5. **Visit the app:**

Open your browser and go to `http://localhost:5000`

##  Future Enhancements

-  Add user login & authentication
-  Save chat history to a database (SQLite, MongoDB, etc.)
-  Dockerize the app for containerized deployment
-  Add support for themes (light/dark mode)
-  Push notifications for new messages
