# 🎵 LyricManager

**LyricManager** is a secure and dynamic web application built using **JSP**, **Java (Servlets)**, **MySQL**, and **Tomcat**.  
It allows users to manage and interact with song lyrics — including posting, viewing, commenting, and reacting — all while ensuring strong data protection through **secure password hashing** and input sanitization.

---

## 🚀 Features

- ✍️ **User Authentication**
  - Secure signup & login with **hashed passwords**
  - Session-based authentication for safety and persistence
- 🎶 **Lyrics Management**
  - Add, edit, view, and delete song lyrics
  - Organized structure with real-time updates
- 💬 **Comment System**
  - Users can comment on lyrics and discuss with others
- ❤️ **Reactions**
  - Like or react to lyrics to engage with the community
- 🔐 **Security-Focused Design**
  - Passwords are **hashed securely** before storing in database  
  - Protected against **XSS**, **CSRF**, and **SQL Injection**
- 🧱 **Follows MVC architecture** for clean code separation

---

## 🧩 Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Frontend** | JSP, HTML5, CSS3, JavaScript |
| **Backend** | Java Servlets |
| **Database** | MySQL |
| **Server** | Apache Tomcat |
| **Architecture** | MVC (Model-View-Controller) |

---

**1. ⚙️ Installation & Setup**

  Clone the repository
  git clone https://github.com/amrishs590/LyricManager.git

**2. Import into Eclipse IDE**

Open Eclipse
Go to File → Import → Existing Projects into Workspace
Choose the project folder

**3. Configure Database**

Create a database:
CREATE DATABASE lyricmanager;
USE lyricmanager;

Then import or run the table creation SQL (shown above).

**4. Update Database Connection**

In DatabaseConnection.java:
String url = "jdbc:mysql://localhost:3306/lyricmanager";
String username = "root";
String password = "your_password";

**5. Deploy on Tomcat**

Add project to Apache Tomcat server
Run it on server
Access at:
👉 http://localhost:8080/LyricManager/
