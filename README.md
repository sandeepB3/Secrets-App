# Secrets-App
A social app wherein users can register/login to post an anonymous secret about themselves. This app is created to demonstrate use of cookies, sessions, security and authentication using passport js and OAuth 2.0

***
### The purpose of this project was to implement the 6 levels of Authentication and Security:
1. Security by storing email and password in mongodb and checking them.
2. Encryption using a SECRET key stored in the .env file
3. Hashing the passwords using md5().
4. Salting and hashing passwords with bcrypt. Its an industry standard security measure. (Hashing using bycrypt has been commented out at the bottom of app.js for user reference).
5. Using passport.js and its various perks such as cookies and sessions.
6. Using OAuth 2.0 – Open Authorization, which enables login through google and facebook services.



