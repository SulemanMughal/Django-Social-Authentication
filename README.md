# Django Social Authentication: Login with Google

A Django-based application demonstrating how to implement Google OAuth2 authentication, allowing users to sign in and sign out using their Google accounts.

## Objectives

By the end of this project, you'll be able to:

* Integrate Google OAuth2 authentication into a Django application.
* Allow users to sign in and sign out using their Google accounts.
* Handle user sessions securely and efficiently.([Python in Plain English][1], [GitHub][2])

## Technologies Used

* **Backend**:

  * ![Django](https://img.shields.io/badge/Django-092E20?logo=django\&logoColor=white) **Django**: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
  * ![Python Social Auth](https://img.shields.io/badge/Python%20Social%20Auth-000000?logo=python\&logoColor=white) **Python Social Auth**: A social authentication/registration mechanism with support for several frameworks and auth providers.([GitHub][3])

* **Frontend**:

  * ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5\&logoColor=white) **HTML5**: For structuring the login and home pages.
  * ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3\&logoColor=white) **CSS3**: For styling the pages.

## Features

* **Google OAuth2 Authentication**: Users can sign in using their Google accounts.
* **Session Management**: Secure handling of user sessions.
* **User Profile**: Displays basic user information fetched from Google.([Python in Plain English][1], [GitHub][4])

## Applications

This integration is ideal for:

* **Web Applications**: Allowing users to sign in using their existing Google accounts.
* **SaaS Platforms**: Simplifying the registration and login process for users.
* **Internal Tools**: Providing easy access for users within an organization.([Medium][5])

## Future Enhancements

To further enhance this project, consider implementing the following features:

* **Additional Social Authentication**: Integrate other social authentication providers like Facebook, GitHub, or LinkedIn.
* **User Profile Management**: Allow users to update their profile information.
* **Email Verification**: Implement email verification for added security.
* **Password Reset Functionality**: Provide users with the ability to reset their passwords.
* **Admin Dashboard**: Create an admin interface to manage users and sessions.([Codeloop][6], [GitHub][7])

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/SulemanMughal/Django-Social-Authentication.git
   cd Django-Social-Authentication
   ```

2. **Create and activate a virtual environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the project dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Google OAuth2 credentials**:

   * Sign up for a Google Developer account at [https://console.developers.google.com/](https://console.developers.google.com/).
   * Create a new project and enable the "Google+ API".
   * Create OAuth 2.0 credentials and obtain your `CLIENT_ID` and `CLIENT_SECRET`.
   * Add your credentials to the Django settings file (`settings.py`):

     ```python
     SOCIAL_AUTH_GOOGLE_OAUTH2_KEY = 'your-client-id'
     SOCIAL_AUTH_GOOGLE_OAUTH2_SECRET = 'your-client-secret'
     ```

5. **Apply database migrations**:

   ```bash
   python manage.py migrate
   ```

6. **Create a superuser** (to access the Django admin panel):

   ```bash
   python manage.py createsuperuser
   ```

7. **Run the development server**:

   ```bash
   python manage.py runserver
   ```

8. **Access the application**:
   Open a browser and go to `http://127.0.0.1:8000/`.

## Contributing

Contributions are welcome! If you would like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.

