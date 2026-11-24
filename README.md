# The Next Generation Institute — Fee Management System

Static website (HTML/CSS/JS), no build step.

## Pages
| File | Purpose |
|---|---|
| `index.html` | Login |
| `forgot-password.html` | Password reset with OTP (simulated WhatsApp/SMS) |
| `dashboard.html` | Stats, overdue students, recent reminders |
| `students.html` | Student list: search, filter, edit, delete |
| `student-form.html` | Add / edit student (`?id=` for edit) |
| `fees.html` | Monthly fee tracker (click month to toggle) |
| `reminders.html` | Overdue check (> 3 unpaid months) and message queue |
| `settings.html` | Admin phone/password, backup export/import, reset |

Demo login: `admin` / `admin123`

## Publish on GitHub Pages
1. Create a new repository and upload all files (keep `css/` and `js/` folders).
2. Repository **Settings → Pages → Branch: main / root → Save**.
3. Open `https://<username>.github.io/<repo>/`.

## Important
This is a front-end demo. Data lives in each browser's localStorage, login is not real security,
and SMS/WhatsApp messages are simulated. For real use you need a backend and an SMS/WhatsApp API.
