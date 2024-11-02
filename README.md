# SmartShield
Photo Attachment: Captures and sends an image to give emergency contacts more context.

# 🛠 Hardware and Software Requirements

# Hardware
Raspberry Pi (e.g., Raspberry Pi 3B+ or later)
Push Button Switch
Jumper Wires
USB Camera (compatible with Raspberry Pi)
Internet Connection (via LAN)

# Software
Operating System: Raspbian OS or similar
Programming Language: Python 3.7+
Required Libraries: smtplib, requests, dotenv (optional for environment variables)

# 📲 Usage Instructions
Power on your Raspberry Pi and ensure it’s connected to the LAN.
Press the emergency button to activate the alert.
The device will:
Capture the current location using LAN.
Capture an image via the USB camera.
Send an email with the location and image to the specified contacts.

# 📷 Example Alert
An example of the email alert includes

Location:https://www.google.com/maps/search/?api=1&query=20.0024,73.7945
Image:![Alert Image](images/WhatsApp Image 2024-11-01 at 08.35.46_08703ab8.jpg)


