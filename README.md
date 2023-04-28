
# Display Current Time and Date

This code for the Digital Clock App uses the setInterval() method to repeatedly call a function called currentTime(), which displays the current time and date on a webpage in real-time. The function uses the JavaScript Date() method to get the current time and date, and formats it in a human-readable way using an array of month names and an array of day names.

## Installation

To use this function on your webpage, simply copy and paste the code into a JavaScript file and link it to your HTML file using a `<script>` tag. Make sure to give the HTML elements that will display the time and date unique IDs so that the function can update them properly.

## Usage

Once the JavaScript file is linked to your HTML file, the setInterval() method will start calling the currentTime() function every 1000 milliseconds (or 1 second), which will update the HTML elements with the current time and date in real-time. The function formats the time and date using various JavaScript methods, including getDay(), getMonth(), getFullYear(), getDate(), getHours(), getMinutes(), and getSeconds(). It also uses conditional statements to format the time in 12-hour clock format with AM or PM.

If you want to customize the way the time and date are displayed, you can modify the code accordingly. For example, you can change the order of the day, month, and year in the date string, or change the way the time is formatted.

Any suggestions and additions are welcome.
