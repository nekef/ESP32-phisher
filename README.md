<H1>ESP32 WiFi Phisher</H1>


<H3>Overview</H3>


This project provides a simple implementation of a WiFi Phisher using an ESP32 or similar device with WiFi capabilities. The code is written in C++ and uses the Arduino framework. The main features include a captive portal for user authentication.

<H3>How it Works</H3>

The program sets up a soft access point with the SSID "172.0.0.1 for WiFi" and an empty password, creating an open network for users to connect to. The captive portal captures HTTP requests and redirects users to a sign-in page with the title "Sign in:". Users are prompted to enter their email and password, and upon submission, the credentials are stored and can be viewed later.

<H3>Web Pages</H3>

Index Page (/): Displays the sign-in form for users to input their credentials.

Post Page (/post): Handles form submissions, validates and stores user credentials, and provides a confirmation message.

Credentials Page (/creds): Displays a list of stored credentials with an option to clear the list.

Clear Page (/clear): Resets the stored credentials list and provides a confirmation message.

<H3>Additional Information</H3>

The project includes basic HTML and CSS styling for a clean and simple user interface.
The code incorporates a basic LED blink function (BLINK()) to indicate activity.
Feel free to customize the code to suit your specific needs or integrate additional features. Please note that this implementation is for educational purposes and may need further security enhancements for production use.

