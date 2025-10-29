# 🔐 Biometric-Based Voting System

## 📘 Overview
The **Biometric-Based Voting System** is a hardware project designed to ensure secure, efficient, and reliable voting using fingerprint authentication.  
The system eliminates the need for manual voter verification, reduces human error, and prevents fake or duplicate voting.

---

## ⚙️ Components Used
- **Arduino UNO** – Main microcontroller board  
- **Fingerprint Sensor Module** – For voter identity verification  
- **LCD Display (16x2)** – To show system status and voting messages  
- **Buzzer** – Indicates success or error during fingerprint scanning  
- **Push Buttons / Switches** – To cast votes  
- **Jumper Wires ** – For circuit connections  

---

## 🧠 Working Principle
1. The voter places their finger on the **fingerprint sensor**.  
2. The system checks the fingerprint against stored templates.  
3. If the fingerprint matches a registered voter:
   - The LCD shows “Access Granted”.
   - The voter can cast their vote using the button system.
4. If not, the LCD shows “Access Denied” and triggers the buzzer.  
5. The data can be later analyzed or displayed for counting results.

---

## 🧩 Files Included
| File | Description |
|------|--------------|
| `Biometric_Voting.ino` | Arduino sketch (main code) |
| `Circuit_Diagram.jpeg` | Circuit connections diagram |
| `Voting_System_Working.mp4` | Demo video of the hardware in action |
| `Voting_System_Image.jpg` | Image of the actual setup |
| `Presentation.pptx` | Project presentation slides |

---

## 🎬 Project Demo
GitHub does not support direct video playback.  
To view the working demo, **download** the file `Voting_System_Working.mp4` from this repository.  
### 🎥 Demo Video
*Note: The demo video file (`Voting_System_Working.mp4`) is included in this repository.  
Please download it to view the hardware demonstration. The video does not contain audio narration.*


---

## 💡 Key Features
- Secure voter authentication using biometrics  
- Simple Arduino-based implementation  
- Real-time feedback on LCD and buzzer  
- Prevents duplicate or fake voting  
- Ideal for smart electronic voting applications  

---

## 🏁 Conclusion
This project demonstrates the integration of **hardware and embedded systems** for a real-world application — a **secure electronic voting system**.  
It highlights how biometrics can enhance the **integrity, reliability, and transparency** of the voting process.

---

