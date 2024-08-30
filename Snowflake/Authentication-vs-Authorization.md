# Authentication vs authorization

Authentication and authorization are both **security processes** that work together to **protect applications and data**:

&nbsp;

## Authentication

Verifies a user's identity, such as when you enter your username and password to log in to a website. The server checks the details against its database to confirm your identity, and then provides you with identification data like a cookie or JWT token. This prevents unauthorized access and keeps your data safe.

&nbsp;

&nbsp;

## Authorization

Determines a **user's level of access** and grants access based on that level.

For example, you're logging in a university portal. First it'll be checked if you're a student or admin or teacher. Then it will give you access according to your role.

Another example, when you go through airport security, you show your ID to authenticate your identity, and then you present your boarding pass to the flight attendant to authorize you to board the plane.

Authorization can also consider environmental attributes like the time of access or location of the data, and resource attributes like the file name or level of data sensitivity. This ensures that users only access what they're permitted to, and prevents accidental or malicious misuse of resources.
