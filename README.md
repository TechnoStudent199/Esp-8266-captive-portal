# Esp-8266-captive-portal
How to Test It:
Upload the Code: Upload the code to your ESP8266 using the Arduino IDE.
Connect to Wi-Fi: Connect your phone, tablet, or computer to the ESP8266 Wi-Fi network (e.g., ESP8266_Captive).
Open Browser: Open a browser and access the captive portal page. The page will adjust itself according to the device size.



How It Works:
User connects to the ESP8266 Wi-Fi (ESP8266_Captive).
The captive portal page is served with fields for the Gmail email and password.
Login Validation:
If the entered Gmail is "user@gmail.com" and the password is "password123", a success message is displayed.
Otherwise, an error message is shown, prompting the user to try again.
No Real Gmail Authentication: This is a simulation. For real Gmail login, you would need to implement OAuth 2.0, which requires a backend server.


Uploading to ESP8266:
Open Arduino IDE and select the appropriate ESP8266 board.
Paste the code into the editor.
Click Upload to upload the sketch to the ESP8266.
Once uploaded, connect your computer or phone to the ESP8266_Captive Wi-Fi network.
Open a browser, and the Instagram-like login page will appear.



How to Use:
Wi-Fi Network: The ESP8266 creates its own Wi-Fi network called "ESP8266_Captive", and anyone who connects to this network will be redirected to the captive portal page.
Login Form: Users can enter their username and password (which are checked in the code). If they enter "user" and "pass", they will see a welcome message; otherwise, they will get an error message.
Gmail Login: Clicking the "Log in with Gmail" button is a placeholder. It doesn’t perform any actual Gmail authentication. This is just for aesthetic purposes to resemble the real Instagram page.
