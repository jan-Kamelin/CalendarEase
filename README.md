CalendarEase
CalendarEase is a simple, web-based calendar application that allows users to add, view, and recover events using cookies and a recovery key. The app is designed with a minimalist look and feel, using navy blue and gray colors.

Features
View a monthly calendar.
Add events with a title and date.
Save events in cookies for persistent storage.
Recover events using a unique recovery key.
Technologies Used
HTML
CSS
JavaScript
FullCalendar.js
js-cookie library
Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

Prerequisites
A web browser (Chrome, Firefox, Safari, etc.)
Installation
Clone the repository or download the project files.
Ensure you have an internet connection to load the FullCalendar and js-cookie libraries from CDN.
Running the Application
Open the index.html file in your web browser.
Usage
Adding Events
Enter the event title and date in the "Add Event" form.
Click the "Add Event" button.
An alert will display your unique recovery key. Save this key to recover your events later.
Recovering Events
Enter your recovery key in the "Recover Events" form.
Click the "Recover Events" button.
The events associated with your recovery key will be displayed on the calendar.
File Structure
CalendarEase/
├── index.html      # Main HTML file
├── style.css       # CSS file for styling
└── README.md       # This README file
External Libraries
FullCalendar.js - A full-sized drag & drop JavaScript event calendar.
js-cookie - A simple, lightweight JavaScript API for handling cookies.
Customization
Colors and Styling
You can customize the colors and styles by modifying the style.css file. The current design uses navy blue and gray for a minimalist look.

CSS (style.css)
/* Base styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

/* Container for the calendar */
#calendar {
    max-width: 900px;
    width: 100%;
    background-color: #ffffff;
    border: 1px solid #ddd;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    border-radius: 8px;
}

/* Calendar header */
.fc-toolbar {
    background-color: navy;
    color: #ffffff;
    border-radius: 6px 6px 0 0;
    padding: 10px;
    text-align: center;
}

.fc-toolbar h2 {
    margin: 0;
    font-size: 24px;
}

.fc-button {
    background-color: gray;
    border: none;
    color: white;
    padding: 10px 20px;
    border-radius: 4px;
    cursor: pointer;
}

.fc-button:hover {
    background-color: navy;
}

.fc-button:focus {
    outline: none;
    box-shadow: 0 0 3px navy;
}

/* Calendar grid */
.fc-daygrid-day {
    border: 1px solid #ddd;
}

.fc-daygrid-day-number {
    color: navy;
    font-weight: bold;
}

/* Event styles */
.fc-event {
    background-color: navy;
    border: none;
    color: white;
    padding: 5px;
    border-radius: 4px;
    font-size: 14px;
}

/* General utility classes */
.text-center {
    text-align: center;
}

.m-0 {
    margin: 0;
}

.p-10 {
    padding: 10px;
}

/* Footer */
.footer {
    text-align: center;
    margin-top: 20px;
    color: gray;
}

.footer a {
    color: navy;
    text-decoration: none;
}

.footer a:hover {
    text-decoration: underline;
}

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License.

Acknowledgments
FullCalendar.js for providing the calendar functionalities.
js-cookie for handling cookies easily.
