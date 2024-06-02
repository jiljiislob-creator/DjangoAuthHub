# DjangoAuthHub
DjangoAuthHub is a comprehensive Django-based project that demonstrates a custom user authentication system with email verification, password reset functionality, and user role management. This project serves as a practical example for developers looking to implement advanced authentication features in their Django applications.

# DjangoAuthHub

**DjangoAuthHub** is a comprehensive Django-based project that demonstrates a custom user authentication system with email verification, password reset functionality, and user role management. This project serves as a practical example for developers looking to implement advanced authentication features in their Django applications.

## Features

1. **Custom User Model**
   - Extends Django's built-in user model to include additional fields like `first_name`, `last_name`, and `email`.
   - Uses email as the primary identifier for authentication instead of the default username.

2. **User Registration with Email Verification**
   - New users can register with their email, which must be verified before account activation.
   - Sends a verification email with a unique activation link to ensure the user's email is valid.

3. **Password Reset Functionality**
   - Allows users to reset their password if they forget it.
   - Sends a secure link to the user's registered email to facilitate the password reset process.

4. **User Roles and Permissions**
   - Implements custom user roles with specific permissions.
   - Controls access to various parts of the application based on user roles.

5. **Comprehensive Testing and Debugging**
   - Includes unit tests for critical functionalities.
   - Utilizes Django’s debug toolbar and logging for effective debugging and performance monitoring.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/DjangoAuthHub.git
   cd DjangoAuthHub
