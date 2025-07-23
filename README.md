# Fire-Fighting-Robot-using-Arduino
An IoT-enabled Fire Fighting Robot designed to detect and extinguish fire automatically using flame sensors, water pump, and DC motors.

# 📁 Project Structure

Fire-Fighting-Robot-IoT/

├── Code/

│   └── code.ino

├── Circuit/

│   └── circuit_diagram.png

├── Images/

│   └── image1.jpg

├── README.md


# 🧰 Components Required

| ⚙️ **Mechanical Components**              | 🔌 **Electronic Components**                  |
| ----------------------------------------- | --------------------------------------------- |
| 🪵 3mm Acrylic Sheet                      | 🧠 Arduino UNO                                |
| 🚗 4-Wheel Robot Car Kit                  | 🔥 Flame Sensor x 3                           |
| 🫗 Water Tank                             | ⚙️ L298 Motor Driver                          |
| 🚿 PVC Water Pipe (8mm)                   | 🤖 Mini Servo Motor SG90                      |
| 🪛 On/Off Switch                          | 🔋 TIP-122 Transistor                         |
| 🔋 18650 Battery Holder – 2 Cell          | 📏 1k Resistor                                |
| 🔋 18650 Battery Cell 3.7V x 2            | 🧪 104pf Capacitor                            |
| 📦 Mounting Hardware / Screws (if needed) | 🔌 Solderless Breadboard                      |
| 🔧 Chassis Assembly Parts                 | 🔌 Male to Male & Male to Female Jumper Wires |
| 🪫 Battery Housing & Power Mount          | 🔌 Female DC Power Jack & 9V 1.5A Adapter     |

# 📸 Project Preview

<p align="center"> 
📝 Image 1: Side view of the robot
<img src="images/image 1.jpg" alt="Fire Fighting Robot - Preview 1" width="300"/> 
📝 Image 2: Robot extinguishing fire
<img src="images/image 2.jpg" alt="Fire Fighting Robot - Preview 2" width="300"/> 
</p>


# ⚙️ Working Principle

Robot continuously scans for fire using 3 flame sensors.
Upon fire detection:
Robot moves toward fire.
Stops at safe distance.
Activates water pump to extinguish the fire.
Sends status to user via Bluetooth or Wi-Fi (IoT-enabled).
Manual override possible through Bluetooth control (optional).

# 🧠 Features

🔍 Real-time flame detection.

💦 Automatic water spray system.

🌐 IoT-enabled (monitoring/control via phone).

⚡ Fast and responsive navigation.

👷‍♂️ Useful in fire-prone industrial or remote areas.

# 🚀 Future Improvements

Add camera module for live video.

Integrate smoke sensors.

Implement cloud-based fire alerts.
