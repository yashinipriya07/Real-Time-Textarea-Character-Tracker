# Real-Time-Textarea-Character-Tracker

Textarea with Real-Time Character Counter

A simple web application that allows users to type a message in a textarea while keeping track of the number of characters typed. The project features a real-time character counter, maximum character limit, and displays a warning message if the user exceeds the limit.

📝 Features

Real-time character count: Updates as the user types.

Maximum character limit: Restricts input to a set number of characters (e.g., 200).

Warning message: Alerts the user if they try to exceed the limit.

Dynamic display: Shows the number of characters typed and remaining.

Prevent over-typing: Extra characters are automatically removed beyond the limit.

📋 How It Works

Textarea Input

Users can type a message in a text area.

Character Counter

Shows the current number of characters typed out of the maximum allowed.

Example: 150/200 characters

Input Validation

Prevents the user from typing more than the maximum allowed characters.

Displays a warning message when the limit is reached.

Real-Time Updates

The counter updates immediately as the user types, deletes, or pastes text.

⚙️ Technologies Used

HTML – Structure of the form and textarea

JavaScript – Real-time character counting and input validation

CSS – Inline styling for error and counter messages

🔧 Usage

Clone the repository:

git clone https://github.com/yashinipriya07/Real-Time-Textarea-Character-Tracker.git


Open the HTML file

Open index.html  in your web browser.

Start Typing

Type a message in the textarea.

Watch the counter update in real time.

If the maximum character limit is reached, typing is blocked, and a warning is shown.

📊 Validation Example
Characters Typed	Counter Display	Status
0	0/200 characters	Valid
50	50/200 characters	Valid
200	200/200 characters	Limit reached
250	200/200 characters	Extra removed
🎨 Optional Enhancements

Add a visual progress bar showing the percentage of characters used.

Highlight the counter in red when approaching the limit.

Add dynamic font resizing or styling changes as the user types.

👤 Author

Name: Yashini Priya S

Developed as a practice project to implement real-time input validation and dynamic UI updates using JavaScript.
