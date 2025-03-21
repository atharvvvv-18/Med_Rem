# Medicine Reminder

This is a simple web application that helps you set reminders to take your medicines. You can enter the medicine name and the time you need to be reminded, and the app will send you a notification at the specified time.

## Features

- Enter the medicine name.
- Set a reminder time in 24-hour format.
- Receive a browser notification at the set time (if notifications are allowed).

## Technologies Used

- HTML
- CSS
- JavaScript

## Files

1. **index.html**: Contains the structure of the page with input fields for medicine name and time.
2. **styles.css**: Provides the styling for the webpage to make it user-friendly.
3. **app.js**: Contains the logic for setting the reminder and sending the notification when the time arrives.

## How to Use

1. Open the `index.html` file in your browser.
2. Enter the name of the medicine you need to be reminded about in the "Enter Medicine Name" field.
3. Set the reminder time in 24-hour format (e.g., `14:30` for 2:30 PM).
4. Click the "Set Reminder" button to set the reminder.
5. If the time matches your set reminder, you will receive a browser notification reminding you to take your medicine.

## Setting Permissions

- When you first set a reminder, the application will ask for permission to send notifications. You need to allow this permission for the reminder notifications to work.
- If you deny the permission, you can manually enable notifications from your browser settings.

## How It Works

- The app checks the current time every minute.
- If the current time matches the time you've set for the reminder, a notification will appear to remind you to take your medicine.
- The reminder notification will show the name of the medicine that you entered.

## Notes

- This app works best on modern browsers that support the Notification API.
- Make sure to allow notifications in your browser to receive reminders.
