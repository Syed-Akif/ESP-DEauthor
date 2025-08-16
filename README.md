# 🚀 ESP32-DEauther

A powerful WiFi testing tool for the **ESP32** that allows you to **deauthenticate devices** connected to nearby WiFi networks.

> ⚠️ **DISCLAIMER**
> This project is intended **for educational and authorized testing purposes only**. Misuse of this tool for illegal activities is strictly prohibited. The developer assumes **no responsibility** for consequences arising from the use of this project. Use it **at your own risk**.

---

## 🔧 Features

* Scan and list nearby WiFi networks
* Launch deauthentication attacks on:

  * Individual networks
  * All detected networks
* Stop active deauth attacks
* Easy-to-use **web interface** hosted directly from the ESP32
* Flash directly from your **browser** or via **PlatformIO**

---

## 📦 Installation

### 🧱 Build from Source (Using PlatformIO)

1. Clone this repo:

   ```bash
   git clone https://github.com/tesa-klebeband/ESP32-Deauther
   ```
2. Install [Visual Studio Code](https://code.visualstudio.com/)
3. Install the [PlatformIO extension](https://platformio.org/install/ide?install=vscode) in VS Code
4. Open the cloned folder in VS Code
5. Click the **Upload** button (✅ icon in the status bar)

---

### 🌐 Flash from Your Browser

1. Open the **[ESP32 Web Flasher](https://tesa-klebeband.github.io/ESP32-Webflasher)** *(Chrome or Edge required)*
2. Select **ESP32-Deauther**
3. Follow the on-screen instructions to flash your device

---

## 📱 Using ESP32-Deauther

Once flashed:

1. Connect to the WiFi network:

   * **SSID**: `ESP32-Deauther`
   * **Password**: `esp32wroom32`
2. Open a browser and go to: `http://192.168.4.1`
3. You’ll be presented with a web interface with the following options:

### Available Actions:

| Action                      | Description                                                                        |
| --------------------------- | ---------------------------------------------------------------------------------- |
| 🔍 **Rescan Networks**      | Scans for all nearby WiFi networks                                                 |
| 💣 **Launch Deauth Attack** | Enter network number and reason code to deauth connected devices                   |
| 🌐 **Deauth All Networks**  | Starts deauth attack across all detected networks (ESP32 reboots required to stop) |
| 🛑 **Stop Deauth Attack**   | Stops the current deauthentication attack                                          |

> 💡 The ESP32's onboard LED will blink during active attacks

---

## 🧾 License

This project is licensed under the [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html). See the [LICENSE](./LICENSE) file for details.

---

## ❤️ Contributing

Pull requests are welcome! If you find bugs or have ideas to improve the project, feel free to open an issue or submit a PR.

---

## 🤝 Acknowledgments

Inspired by other open-source deauther projects for ESP8266 and ESP32 platforms.

