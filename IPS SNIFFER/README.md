
## Project Tutorial: ESP32 Network Monitor with Telegram Alerts

### Overview
This project involves creating a Network Monitor using an ESP32 microcontroller. The monitor will keep an eye on devices that connect to your local Wi-Fi network and send you alerts via Telegram whenever a new device connects.

### Prerequisites
Before starting, make sure you have the following:

- ESP32 development board
- A Wi-Fi network (SSID and password)
- A Telegram account
- Arduino IDE installed
- Required libraries (listed in the code)

### Step 1: Set Up Telegram Bot
1. Open your Telegram messenger and search for "BotFather."
2. Send the command `/newbot` to create a new bot. Follow the instructions to name your bot and obtain a bot token.
3. Search for "IDBot" and send the command `/getid` to get your Chat ID.

### Step 2: Set Up Arduino IDE
1. Install the Arduino IDE if you haven't already.
2. Install the necessary libraries mentioned in the code, including `ezTime`, `WiFiManager`, `ArduinoJson`, `UniversalTelegramBot`, and others. You can add libraries through the Arduino Library Manager.

### Step 3: Configure ESP32
1. Connect your ESP32 to your computer.
2. Open the code provided in your Arduino IDE.
3. Replace the placeholders in the code with your Wi-Fi SSID, password, Telegram Bot Token, and Chat ID.

### Step 4: Upload Code to ESP32
1. Select the correct board and COM port in the Arduino IDE.
2. Click the "Upload" button to upload the code to your ESP32.

### Step 5: Monitor Network Activity
1. Your ESP32 will now continuously monitor network activity.
2. Whenever a new device connects to your network, you'll receive a Telegram alert with details about the device, including its MAC address, IP address, and, if available, its device name.

### Step 6: Additional Commands
- You can use the following commands in your Telegram chat with the bot:
  - "mute": Mutes all messages.
  - "unmute": Unmutes messages.
  - "help": Displays information about the project and available commands.

### Step 7: Explore Further
- Explore the code to understand how it works and customize it to fit your needs.
- Experiment with different projects and sensors based on this foundation.

### Step 8: Share Your Projects
- If you create exciting projects based on this setup, share them with the community on platforms like GitHub, forums, or your YouTube channel.

Happy tinkering and building!
