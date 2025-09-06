# 🔐 Django REST Framework Authentication API with Simple JWT

This project is a **complete authentication system** built with **Django REST Framework (DRF)**, featuring **JWT-based authentication** using **Simple JWT**.  
It provides endpoints for **user registration, login, logout, password reset, profile management, and token handling**.

This API is perfect for integrating secure authentication in any Django-based web or mobile application.

---

## 🛠️ Features

- **User Registration** – Create new users with email, username, and password.  
- **Login / Logout** – JWT-based login and logout functionality.  
- **Token Management** – Issue, refresh, and blacklist tokens using Simple JWT.  
- **Profile Management** – View and update authenticated user profile.  
- **Password Management** – Change and reset passwords securely.  
- **DRF Serializers & Views** – Modular, reusable serializers and views for scalability.  
- **Postman Collection** – Pre-configured Postman requests for easy testing.  

---

## 🧰 Tech Stack

- **Backend:** Django 5+, Django REST Framework  
- **Authentication:** Simple JWT  
- **Database:** SQLite (default, can be changed to PostgreSQL/MySQL)  
- **Testing:** Postman (via provided collection)  
- **Python Version:** 3.12+  

---
---

📬 Testing the API
	•	Import the file DjangoAuthAPI.postman_collection.json into Postman.
	•	All API endpoints are pre-configured with request body examples and headers.
	•	You can quickly test register, login, token refresh, profile, and password management.

⸻

💡 Notes & Best Practices
	•	JWT Expiration: Access tokens are short-lived; refresh tokens should be securely stored.
	•	Security: Never expose refresh tokens in frontend code.
	•	Extensibility: Add more user fields (profile picture, bio) easily in users/models.py.
	•	Deployment: Use environment variables for SECRET_KEY and database credentials.

⸻

📜 License

This project is open-source under the MIT License.

⸻

📧 Contact
	•	Author: Sani Jain
	•	GitHub: @sanij0579


