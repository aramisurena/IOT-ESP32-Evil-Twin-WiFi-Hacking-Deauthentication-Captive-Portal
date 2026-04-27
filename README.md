[![Github issues](https://img.shields.io/github/issues/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/issues)
[![Github forks](https://img.shields.io/github/forks/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/network/members)
[![Github stars](https://img.shields.io/github/stars/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/stargazers)
[![Top language](https://img.shields.io/github/languages/top/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)

---

## 🧠 Tags

`ESP32` `IoT` `WiFi Hacking` `Deauthentication` `Captive Portal` `Microcontroller Security` `Arduino`

---

---

# 🚨 ESP32 Evil Twin WiFi Hacking | Deauthentication & Captive Portal 🚨

> **Disclaimer:** This project is for **educational purposes only**. Use it responsibly and legally. Unauthorized attacks on networks are illegal in most countries. 🌐🔒

---

![Profile Views](https://komarev.com/ghpvc/?username=aadesh0706&color=blue)  
*Active since*: `September 2024`

**Account From:** `September 2020`

---

### 🎥 **Demo Video**

Check out the demo of this project in action! 🎬  
[![ESP32 Evil Twin WiFi Hacking](https://img.youtube.com/vi/AEb33trYEAY/0.jpg)](https://www.youtube.com/shorts/AEb33trYEAY)  
Click the thumbnail or follow [this link](https://www.youtube.com/shorts/AEb33trYEAY) to watch.

---

### 🎯 **Project Overview**

This repository demonstrates how to execute an **Evil Twin WiFi Hacking** attack using an **ESP32** module. The attack forces users off their legitimate network by sending **deauthentication packets** and lures them into connecting to a fake access point where a **captive portal** captures their WiFi credentials. 

The project leverages **HTML**, **CSS**, and **JavaScript** to build a custom front-end for the captive portal, making it look like a legitimate login page.

---

## 🚀 **Features**
- 🛑 **Deauthentication Attack**: Disconnects devices from their current WiFi network.
- 🌐 **Captive Portal**: A fake login page where users unknowingly enter their WiFi credentials.
- 🎨 **Custom Frontend**: Built using **HTML**, **CSS**, and **JavaScript** for user interaction.
- 📡 **ESP32 Integration**: WiFi hacking on a powerful yet affordable ESP32 module.

---

## 🛠️ **Setup and Installation**

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal.git
cd IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal
```

### 2️⃣ **Install Required Libraries**

Make sure you have the necessary libraries and tools installed to program the ESP32:

- **ESP32 Core for Arduino**: [Install Guide](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)

### 3️⃣ **Upload the Code to ESP32**
1. Open the `esp32_deauth_attack.ino` file in your Arduino IDE.
2. Connect your ESP32 to your computer via USB.
3. Select your ESP32 board from the Tools > Board menu.
4. Click **Upload**.

### 4️⃣ **Customize the Captive Portal**
- The captive portal files are located in the `html/` folder. 🎨
- You can easily edit the design using **HTML**, **CSS**, and **JavaScript** to match your desired look and feel.

---

## ⚡ **How to Run the Attack**

1. **Launch the Deauthentication Attack**: 📶 Force devices off the legitimate WiFi network.
2. **Start the Fake AP**: 🖧 Broadcast your rogue access point.
3. **Use the Captive Portal**: 🌐 When users attempt to reconnect, they are directed to a fake login page.
4. **Capture WiFi Credentials**: 🔐 Credentials entered by users are logged on the ESP32.

---

## 📂 **Files Included**
- `esp32_deauth_attack.ino`: The main code for the deauthentication attack.
- `html/`: Contains all the files for the captive portal (HTML, CSS, JavaScript).
- `README.md`: Overview, setup instructions, and usage information.

---

## 🔗 **How It Works**

1. **Deauthentication Attack**: The ESP32 sends deauth packets to disconnect devices from their original network.
2. **Rogue Access Point**: After being disconnected, the ESP32 broadcasts a rogue AP with a similar name (SSID) to the legitimate one.
3. **Captive Portal**: When users attempt to connect to the rogue AP, they are redirected to a fake login page asking for WiFi credentials.
4. **Credentials Logged**: Any credentials entered are captured and stored on the ESP32.

---

## 💻 **Technologies Used**
- **ESP32**: Low-cost WiFi module.
- **HTML**: Structure for the captive portal.
- **CSS**: Styling for a user-friendly portal interface.
- **JavaScript**: Handles user interactions and form submissions.

---

## 🚧 **Future Improvements**
- 🔒 Add encryption to securely transmit credentials.
- 📊 Create a log file to store captured credentials.
- 🔧 Improve the accuracy of deauthentication attacks.

---

## 👨‍💻 **Contributing**

Want to improve this project? Feel free to fork the repository, make changes, and submit a pull request. Contributions are always welcome! 🛠️

---

## 📝 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 📜

---

## ⚠️ **Disclaimer**

This project is intended for **educational and ethical testing purposes** only. **Do not** use this code to target any WiFi network without explicit permission from the network owner. Always comply with local laws and regulations.

---

### 📦 **Repository Tags**
```
ESP32, Evil Twin, WiFi Hacking, Deauthentication, Captive Portal, HTML, CSS, JavaScript, Cybersecurity, Ethical Hacking, ESP32 WiFi, IoT, WiFi Pentesting
```

---

### ARAMIS_URENA: NOTES FOR CSN150
### EQUIPMENT USED: 
- EPS32-Cam
- iPhone
- Windows Computer
- USB A to C Data Cable
  
### TOOLS USED:
-Arduino
-GPT-5.3
-GitHub

### STEPS I FOLLOWED: 
1. Forked the provided GitHub repository.
2. Uploaded the `.ino` file into Arduino IDE.
3. Installed and configured ESP32 board support.
4. Selected the correct board and COM port.
5. Fixed compilation errors caused by:
   - Improper string formatting
   - Unescaped quotation marks in HTML
6. Rebuilt the HTML interface to properly render in Arduino.
7. Modified the code to:
   - Use a controlled lab SSID instead of cloning real networks
   - Disable deauthentication features
   - Replace real password handling with demo input logging
8. Uploaded the corrected code to the ESP32-CAM.
9. Connected my iPhone to the ESP32 access point.
10. Opened `http://192.168.4.1` in a browser.
11. Verified that the captive portal page loaded.
12. Entered test input and confirmed it appeared in the Serial Monitor.

### PROBLEMS/SOLUTIONS:
### Problems Encountered / Solutions (Evil Twin Assignment)

---

**Problem 1: ESP32 Access Point Not Appearing**
- Cause:
  The program did not reach the `WiFi.softAP()` function due to earlier code errors.
- Solution:
  Fixed compilation and runtime issues so the ESP32 could properly initialize and create the access point. Once corrected, the network `EvilTwin-Lab-Demo` became visible on my iPhone.

---

**Problem 2: Captive Portal Not Loading Properly**
- Cause:
  The DNS server and web server were not correctly redirecting traffic to the ESP32, or the page failed to render due to HTML issues.
- Solution:
  Verified DNS redirection using:
  ```cpp
  dnsServer.start(53, "*", apIP);

**Problem 3: Compilation Errors from HTML Strings**

Errors:
operator""width
operator""UTF
missing terminating character
Cause:
Improperly formatted HTML strings in Arduino code (quotes not escaped correctly).
Solution:
Escaped internal quotes using \"

Rewrote broken lines such as:

"<meta name=\"viewport\" content=\"width=device-width,initial-scale=1\">"
"<meta charset=\"UTF-8\">"
Cleaned and rebuilt the header() function to properly structure HTML output

**Problem 4: Original Code Too Complex / Unstable**

Cause:
The original GitHub code included unnecessary complexity such as:
SSID cloning
Deauthentication logic
Real credential validation
Solution:
Simplified and stabilized the code while preserving core Evil Twin functionality:
Replaced real SSID cloning with a controlled lab SSID (EvilTwin-Lab-Demo)
Disabled deauthentication features
Removed real WiFi connection attempts
Kept captive portal and user input simulation

**Problem 5: Verifying Evil Twin Functionality**

Issue:
Initially unclear how to confirm the Evil Twin was working correctly.
Solution:
Established a testing method:
Connect to ESP32 WiFi network (EvilTwin-Lab-Demo)
Open browser and navigate to http://192.168.4.1
Confirm captive portal page loads
Enter test input
Verify Serial Monitor output:

**Problem 6: Simulating a Realistic Evil Twin**

Issue:
The project originally attempted to clone real nearby networks, which could be unsafe or unreliable.
Solution:
Used a controlled lab SSID and focused on simulating the user experience instead of cloning real networks. This allowed demonstration of:
Fake network creation
Captive portal interaction
User input capture (simulation only)

### FINAL REPORT ###

For this project, I was able to use my ESP32-CAM to simulate an Evil Twin attack. I created a fake WiFI access point with the ESP32 that mimics a legitmate network login page. From here, any user who connects will have the data they input captured in my serial monitor. In this case, the password "aramis123" was captured when I connected to the EvilTwin-Lab-Demo access point I set up.
  

