# Apex AI

Apex AI is a friendly learning-space prototype for student questions, study groups, and teacher conversations.

## Run it

Open `index.html` in a modern browser. No package installation, build step, or development server is required.

## What works in this prototype

- Ask questions in the AI assistant. Online answers use Pollinations AI; common greetings receive an immediate friendly reply, and built-in study guides are used if the service is unavailable.
- Start a new assistant chat or reopen a saved conversation from chat history. The earlier seeded tutor transcript is cleared when upgrading to this version.
- Render online Markdown answers through DOMPurify. Keep up to six recent question/answer exchanges per chat in this browser for context, with a clear-memory control.
- Create study groups and exchange messages in the browser.
- Browse sample teacher conversations and write messages.
- Add, complete, and remove agenda tasks. Chats, agenda tasks, profile, and theme preference persist in this browser.
- Log in to a local demo profile with a name, email, and one-time verification code.
- Use the responsive layout on desktop and mobile screens.
- Get a greeting based on local time and a color theme that follows the device's light or dark setting.

## Important limits

Online questions are sent to Pollinations AI. Anonymous use is rate-limited, and availability, accuracy, and response quality are not guaranteed. Built-in study guides are only a fallback, not a live AI answer. Verify important information with class materials or a teacher.

The login verification code is generated and displayed in the app; it is not emailed. The name and email are stored only in this browser, so this is not secure authentication and cannot send announcements. Group and teacher messages also stay in this browser; they are not delivered to classmates or teachers. Do not enter private or sensitive student information.

A production version would need secure authentication with email verification, a mail service, user accounts and permissions, persistent shared chat storage, and school-approved privacy and safety controls. Keep all provider credentials on the server, never in browser code.
