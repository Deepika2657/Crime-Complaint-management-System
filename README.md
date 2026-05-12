 **Crime Complaint Management System** 
 
 project:

---

# Crime Complaint Management System

A Full Stack web-based application developed to simplify and manage crime complaint registration and tracking processes digitally. The system enables users to register complaints, track complaint status using a unique complaint ID, and receive updates from the crime department teams. Administrators can manage complaints, assign department teams, update case status, and maintain records efficiently.

## Features

* User Registration and Login
* Complaint Registration and Tracking
* Unique Complaint ID Generation
* Admin Dashboard for Complaint Management
* Department Team Assignment
* Complaint Status Updates
* Secure Authentication System
* MySQL Database Integration

## Technologies Used

* Frontend: HTML, CSS,JS
* Backend: Flask
* Database: MySQL

## Modules

* User Module
* Admin Module
* Department Team Module
* Complaint Tracking System

## Project Objective

The main objective of this project is to provide an efficient and transparent online platform for managing crime complaints and improving communication between users and crime department teams.

# Crime Complaint Management System Using Flask

## Project Flow

```text id="jlwm13"
Frontend → Flask Backend → MySQL Database
```

---

# Technologies Used

| Technology     | Purpose             |
| -------------- | ------------------- |
| HTML           | Webpage structure   |
| CSS            | Styling             |
| JavaScript     | Form validation     |
| Flask (Python) | Backend development |
| MySQL          | Database storage    |

---

# Step-by-Step Process

## Step 1: User Opens Website

### Frontend Used

```text id="jlwm14"
HTML + CSS + JavaScript
```

Pages:

* Home Page
* Login Page
* Complaint Form

---

## Step 2: User Registers/Login

### JavaScript Validation

Checks:

* Empty fields
* Email format
* Password validation

After validation → data sent to Flask backend.

---

## Step 3: Flask Receives Request

### Backend Used

```text id="jlwm15"
Flask (Python Framework)
```

Flask routes handle requests.

Example:

```python id="jlwm16"
@app.route('/login', methods=['POST'])
```

Flask:

* Receives user data
* Processes request
* Checks credentials

---

## Step 4: Flask Connects MySQL

### Database Connection

Using:

```text id="jlwm17"
MySQL Connector / SQLAlchemy
```

Flask stores:

* User details
* Complaint details
* Complaint status

---

## Step 5: Complaint Registration

System generates:

```text id="jlwm18"
Unique Complaint ID
```

Complaint stored in database.

Example data:

* User Name
* Complaint Type
* Date
* Status

---

## Step 6: Admin Module

Admin can:

* View complaints
* Assign department teams
* Update complaint status
* Close complaints

---

## Step 7: Complaint Tracking

User enters:

```text id="jlwm19"
Complaint ID
```

Flask fetches complaint status from MySQL and displays current progress.

---

## Step 8: Complaint Closure

When case is closed:

* Status updated
* User notified
* Complaint removed after completion

---

# Backend Responsibilities Using Flask

```text id="jlwm20"
• Handle user requests
• Process complaint data
• Validate login credentials
• Connect database
• Manage complaint status
• Send responses to frontend
```

---


---

# GitHub Overview Short Version


A Full Stack Crime Complaint Management System developed using Flask and MySQL for online complaint registration, complaint tracking, admin management, and secure database operations.
```
1. User opens the website using a browser.

2. Frontend pages are created using HTML, CSS, and JavaScript.

3. User registers or logs into the system.

4. JavaScript validates the form inputs before submission.

5. Form data is sent from frontend to Flask backend through HTTP requests.

6. Flask routes receive and process user requests.

7. Flask connects to MySQL database using MySQL Connector/SQLAlchemy.

8. Complaint details, user data, and status information are stored in the database.

9. Admin views complaints, assigns department teams, and updates complaint status.

10. Users track complaint status using Complaint ID and receive updates from the system.





##By

* KASTALA DEEPIKA
To run a **Flask project**, you need:

* Python installed
* Flask library installed
* Terminal / Command Prompt
* VS Code or PyCharm (recommended)

---

# Step-by-Step Run Flask Project

## 1. Install Python

Download from:

[Python Official Website](https://www.python.org/downloads/?utm_source=chatgpt.com)

While installing:
✔ Check **“Add Python to PATH”**

---

# 2. Install VS Code

Download:

[Visual Studio Code](https://code.visualstudio.com/?utm_source=chatgpt.com)

Install:

* Python extension in VS Code

---

# 3. Open Project Folder

Example project:

```text
crime_project/
│
├── app.py
├── database.py
├── templates/
├── static/
```

Open this folder in VS Code.

---

# 4. Open Terminal

In VS Code:

```text
Terminal → New Terminal
```

Shortcut:

```text
Ctrl + `
```

---

# 5. Install Flask

In terminal run:

```bash
pip install flask
```

---

# 6. Create Database

Run:

```bash
python database.py
```

Output:

```text
Database Created
```

---

# 7. Run Flask App

Run:

```bash
python app.py
```

Output:

```text
* Running on http://127.0.0.1:5000
```

---

# 8. Open Browser

Open:

```text
http://127.0.0.1:5000
```

Now your website runs.

---

# Where Flask Runs

| Component      | Runs Where    |
| -------------- | ------------- |
| HTML/CSS/JS    | Browser       |
| Flask (Python) | Local Server  |
| SQLite         | Database File |

---

# Technologies Needed

| Purpose  | Software       |
| -------- | -------------- |
| Backend  | Python + Flask |
| Editor   | VS Code        |
| Browser  | Chrome         |
| Database | SQLite         |

---

# Important Flask Files

| Folder/File | Purpose         |
| ----------- | --------------- |
| app.py      | Main backend    |
| templates   | HTML pages      |
| static      | CSS & JS        |
| database.db | SQLite database |

---

# Flask Run Command Summary

```bash
pip install flask
python database.py
python app.py
```

Then open:

```text
http://127.0.0.1:5000
```



