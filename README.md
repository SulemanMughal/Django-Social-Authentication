# Django Social Authentication: Login with Google

![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Google OAuth2](https://img.shields.io/badge/Google%20OAuth2-4285F4?logo=google&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Open Source](https://img.shields.io/badge/Open%20Source-✔️-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey) <!-- Add your license if available -->

> **Seamless, secure, and modern authentication for Django web apps using Google OAuth2.**

---

## 🚀 Taglines

- **"Sign In. Securely. Socially."**
- **"Modern authentication for modern Django apps."**

---

## ✨ Features

- **Google OAuth2 Authentication**: Users can sign in using their Google accounts.
- **Session Management**: Secure handling of user sessions.
- **User Profile**: Displays basic user information fetched from Google.
- **Minimalistic Frontend**: Clean, responsive pages using Bootstrap, HTML5, and CSS3.

---

## 🎯 Objectives

- Integrate Google OAuth2 authentication into a Django application.
- Allow users to sign in and sign out using their Google accounts.
- Handle user sessions securely and efficiently.

---

## 🛠️ Technologies Used

- ![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white) **Django**: High-level Python web framework.
- ![Python Social Auth](https://img.shields.io/badge/Python%20Social%20Auth-000000?logo=python&logoColor=white) **Python Social Auth**: Flexible social authentication for Django.
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) **HTML5**: Markup for login and home pages.
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) **CSS3**: Modern page styling.
- ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white) **Bootstrap**: Responsive design.

---

## 🏷️ Tags

`django` `authentication` `social-auth` `google-oauth2` `python` `login` `webapp`

---

## 💡 Applications

- **Web Applications**: Let users sign in with Google.
- **SaaS Platforms**: Simplify registration and login.
- **Internal Tools**: Easy access for organization members.

---

## 🧩 Future Enhancements

- Add more social authentication providers (Facebook, GitHub, LinkedIn, etc.).
- User profile management and editing.
- Email verification and password reset.
- Admin dashboard for user/session management.

---

## 📦 Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/SulemanMughal/Django-Social-Authentication.git
    cd Django-Social-Authentication
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Configure Google OAuth2 credentials:**
    - Visit [Google Developer Console](https://console.developers.google.com/).
    - Create a new project, enable "Google+ API".
    - Create OAuth 2.0 credentials, get your `CLIENT_ID` and `CLIENT_SECRET`.
    - Add these to your `settings.py`:

      ```python
      SOCIAL_AUTH_GOOGLE_OAUTH2_KEY = 'your-client-id'
      SOCIAL_AUTH_GOOGLE_OAUTH2_SECRET = 'your-client-secret'
      ```

5. **Run migrations:**

    ```bash
    python manage.py migrate
    ```

6. **Create a superuser:**

    ```bash
    python manage.py createsuperuser
    ```

7. **Start the development server:**

    ```bash
    python manage.py runserver
    ```

8. **Access the app:**  
   Visit `http://127.0.0.1:8000/`.

---

## 🤝 Contributing

Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

---

## 🔗 Useful Links

- [Django Documentation](https://docs.djangoproject.com/)
- [Python Social Auth Docs](https://python-social-auth.readthedocs.io/en/latest/)
- [Google OAuth2 Guide](https://developers.google.com/identity/protocols/oauth2)

---

## 🧑 Author

- [Suleman Mughal](https://github.com/SulemanMughal)

---

## ⭐ Show your support

Give a ⭐️ if you found this project useful!

---

<!-- You can add a project logo or banner here if available. -->
