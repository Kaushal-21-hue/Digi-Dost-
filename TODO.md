# TODO: Fix 404 Error for /api/auth/reset-password

- [x] Add POST /reset-password endpoint in Backend/routes/auth.js
  - Find user by email
  - Hash new password with bcrypt
  - Update and save user
  - Return success message
  - Handle errors (user not found, server error)
