# Laravel 5 Boilerplate

Boilerplate for website with frontend and backend (admin) pages.

## Setup

This setup by default have users and admin_users table and their respective models and AuthControllers. Views for the admin is in the folder resources/views/admin. You can change the name to your liking.

#### Config

Check the app/auth.php.

#### Middleware

Check app/Http/Middleware/Authenticate.php. Define login redirect path for each guard if you are attempting to access a page that require auth credentials.
