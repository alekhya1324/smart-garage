# smart-garage
# Smart Garage System with Bolt IoT and Arduino

This project enables you to create a smart garage system using Bolt IoT and Arduino. The Bolt IoT module is used to send the garage door status to the Bolt Cloud, allowing you to monitor whether the garage is open or closed remotely.

## Hardware Requirements:
- Arduino board
- Bolt IoT module
- Relay module or digital sensor for garage door status
- WiFi module (e.g., ESP8266)

## Software Requirements:
- Arduino IDE
- Bolt IoT Arduino library

## Setup Instructions:

1. **Install Libraries:**
   - Open Arduino IDE.
   - Install the Bolt IoT Arduino library. You can find it on the Arduino Library Manager.

2. **Connect Hardware:**
   - Connect the Bolt IoT module to the Arduino using SoftwareSerial pins (RX on Bolt to TX on Arduino, TX on Bolt to RX on Arduino).
   - Connect the relay module or digital sensor for garage door status to a digital pin on the Arduino (e.g., pin 2).

3. **Configure Bolt IoT:**
   - Create a Bolt IoT account and add your Bolt device.
   - Obtain the API key and device ID from your Bolt Cloud account.
   - Update the `API_KEY` and `DEVICE_ID` variables in the Arduino code.

4. **Upload Code:**
   - Connect Arduino to your computer using a USB cable.
   - Open the Arduino IDE, load the provided code, and upload it to the Arduino.

5. **Monitor Data:**
   - Open the Arduino Serial Monitor to view the status of the garage door being sent to the Bolt Cloud.

6. **Run the Project:**
   - Power up the Arduino and observe the garage door status being updated on the Bolt Cloud.

7. **Access Data Remotely:**
   - Log in to your Bolt Cloud account to check the real-time status of your garage door.

Enjoy your Smart Garage System with Bolt IoT and Arduino!
