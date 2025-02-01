# CS50 Project 3 - Mail

This project is a single-page email client developed for CS50's Web Programming with Python and JavaScript course. The application mimics basic email functionalities, allowing users to send, receive, and manage emails using a clean and interactive interface. The project is built using Django for the backend and JavaScript for the frontend.

## Demo

A short video walkthrough of the project specifications: [https://youtu.be/mtI8MI4b0pc](https://youtu.be/mtI8MI4b0pc)

### Test Login Credentials

|          Email Address           |  Password  |
|----------------------------------|------------|
|         john@example.com         |  password  |

## Project Requirements

### Core Features

1. **User Authentication**:
   - Users can register for an account, log in, and log out.
   - The application displays different content based on whether a user is signed in.

2. **Email Composition**:
   - Users can compose new emails by entering recipients, subject, and body.
   - Emails are sent and stored in the database without being sent to real email servers.

3. **Mailbox Navigation**:
   - Users can navigate between their Inbox, Sent, and Archived emails.
   - Each mailbox displays a list of emails with relevant details such as sender, subject, and timestamp.

4. **View Email**:
   - Users can click on an email to view its full content, including sender, recipients, subject, timestamp, and body.
   - Emails are marked as read when viewed.

5. **Archive and Unarchive Emails**:
   - Users can archive emails from their Inbox and unarchive them from the Archive mailbox.
   - This functionality allows for better email management.

6. **Reply to Emails**:
   - Users can reply to emails, with the reply form pre-filled with the original sender's address and a formatted subject line.
   - The body of the reply includes a quoted section of the original email.

7. **Responsive Design**:
   - The application is designed to be user-friendly and responsive, ensuring a smooth experience across different devices.

---

## Additional Notes

- **JavaScript and AJAX**: The application uses JavaScript to handle user interactions and AJAX requests to communicate with the backend API without reloading the page.
- **Error Handling**: The application provides clear feedback for actions such as sending emails and archiving/unarchiving.
- **Extensibility**: The design and code structure allow for future enhancements and additional features.

---

## Running the Application

To start the application, follow these steps:

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

2. Running migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   
2. Start the application
   ```bash
   python manage.py runserver


## Build static assets

To build static assets, follow these steps:

```bash
python manage.py collectstatic