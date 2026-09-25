# Accounts

Manage admin and engineer accounts. Customer accounts are managed separately.

## Creating Accounts

**Who can create:**
- Admin: can create engineer accounts

**Required fields:**
- Email (becomes the login username)
- Password (10+ characters with uppercase, lowercase, numbers, and special character)
- Full name
- Contact number (UK format)
- Emergency contact (required for engineers, optional for admins)
- Tier (engineers only)

## Editing Accounts

Email cannot be changed after account creation. All other fields can be updated.

## Account Status

**Active accounts** can log in and access the platform.

**Suspended accounts** cannot log in. However, if an engineer is already logged in when suspended, they will not be immediately logged out. Their existing session remains active until it expires naturally.

**Important:** Suspending an engineer does not remove their existing schedule assignments. To prevent new job assignments, delete the engineer's schedules from the Schedules screen.

## Password Resets

Admins can send password reset emails to any account. The user will receive instructions to reset their password.

## Permissions

- **Admin**: Create engineers, edit any account, suspend/reactivate accounts, reset passwords
- **Engineer**: View own profile only (managed via Profile screen)
