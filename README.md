🗳️📟 ESP32 based Voting Machine
----------------------------------------------------
A simple Voting Machine Project using ESP32, 3 push buttons, and an I2C LCD display. Each button represents a candidate, and votes are displayed on the LCD.

----------------------------------------------------
🚀 Features
----------------------------------------------------
✅ 3 Candidates (3 Buttons)


✅ Vote counting system


✅ LCD display (16x2 I2C)


✅ Auto display vote for 3 seconds


✅ LCD turns OFF after each vote


✅ Simple and beginner-friendly

----------------------------------------------------
🛠️ Components Required
----------------------------------------------------
- ESP32
- 16x2 I2C LCD Display
- 3 Push Buttons
- Jumper Wires
- Breadboard

----------------------------------------------------
🔌 Circuit Connections
----------------------------------------------------

| LCD Pin | ESP32 Pin |
| ------- | --------- |
| VCC     | 5V        |
| GND     | GND       |
| SDA     | GPIO 21   |
| SCL     | GPIO 22   |

| Button   | ESP32 Pin |
| -------- | --------- |
| Button 1 | GPIO 32   |
| Button 2 | GPIO 33   |
| Button 3 | GPIO 14   |

-----------------------------------
💡 How It Works
----------------------------------
System starts and LCD shows "Voting Machine"

LCD turns OFF after initialization

When a button is pressed:
-Vote count increases
-LCD turns ON
-Displays selected candidate vote
-After 3 seconds, LCD turns OFF
- Process repeats for each vote

------------------------------------------
Future Improvements
------------------------------------------
🏆 Winner display


🔘 Result button


🔄 Reset button


📶 WiFi-based voting system

---------------------------------------
🧪 Simulation
----------------------------------------
Simulation by Wokwi
