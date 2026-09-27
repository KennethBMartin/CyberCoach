# Project CyberCoach (Open-Source Autonomous Health Loop)
Project CyberCoach is a 100% free, open-source, closed-loop behavioral modification system. It connects to everyday wearables, tracks your metabolic or behavioral telemetry locally, and uses a local AI agent to whisper real-time behavioral nudges into your earbud—completely removing the exhausting burden of willpower. This system is modularly designed to target multiple behavioral interventions, including sugar intake/weight management, smoking/vaping cessation, and micro-habits like compulsive nail-biting or cheek chewing.

---

## ⚖️ CRITICAL LEGAL NOTICE & LIABILITY WAIVER
**USE ENTIRELY AT YOUR OWN RISK.**
This software is provided "AS IS", without warranty of any kind, express or implied. 
* **No Medical Advice:** This is an experimental behavioral feedback tool. It is NOT a medical device, a treatment for clinical obesity, substance addiction, or a substitute for professional medical care. 
* **Zero Liability:** The creators, contributors, and maintainers of this project assume ABSOLUTELY NO LIABILITY for physical health outcomes, psychological impacts, or the behavior of smart-home appliances connected to this system. 
* **Safety Warning:** If you have a history of eating disorders, metabolic illnesses, psychiatric conditions, or are under medical supervision, DO NOT deploy this software. By installing this system, you agree to assume 100% of the risk.

---

## 🔒 Security & Privacy Architecture (The "Iron Curtain" Model)
To guarantee that your private health data is never sold, tracked, or weaponized for profit, the system enforces strict architectural boundaries:

* **100% Local Execution:** The AI coach runs entirely on your phone's onboard hardware (NPU). No data is ever sent to external cloud servers.
* **SHA-256 Passcode Hashing:** Your local data vault is encrypted using AES-256 keys derived from a SHA-256 hashed master passcode. Your actual password is never stored on the device.
* **Tamper Verification:** Every official release includes a unique SHA-256 checksum. Always verify the checksum before installing to guarantee the code has not been maliciously altered.
* **Total Offline Capability:** You can completely revoke internet permissions for this app in your phone settings. The system functions perfectly while completely disconnected from the web.

---

## 🛠️ The Minimalist Hardware Shopping List
The system is entirely modular. You can get started using basic hardware you likely already own.

| Component Type | Purpose | Low-Cost / Free Option | Premium Precision Option |
| :--- | :--- | :--- | :--- |
| **The Brain** | Processes the data & runs local AI | Your existing smartphone | Modern phone with an AI NPU chip |
| **The Voice** | Delivers ambient audio nudges | Any standard Bluetooth Earbud | Bone-conduction sports headphones |
| **Biometric Sensor** | Tracks sleep, heart rate, & recovery | Budget fitness band (e.g., Xiaomi) | Open Wearables compatible Smart Ring |
| **Habit Trackers** | Captures real-time actions | Smartphone microphone/camera | Smart band with Hand-to-Mouth tracking |
| **Metabolic Sensor** | Tracks real-time glucose spikes | *Optional:* None (Relies on data models) | Dexcom Stelo or Abbott Lingo CGM |
| **Physical Friction** | Enforces physical boundaries | *Optional:* None (Audio nudges only) | Tuya/Zigbee Smart Cabinet Lock |

---

## 🚀 3-Step Setup Guide (No Coding Required)
1. **Download:** Grab the latest compiled app wrapper from the GitHub Releases tab (and verify the SHA-256 checksum).
2. **Connect Wearables:** Tap "Connect Health Data" to sync your existing health app (Apple Health, Health Connect, or Garmin) via the built-in Open Wearables protocol.
3. **Set Your Nudge/Reward Threshold:** Adjust the behavioral slider from Level 1 (Gentle Guide) to Level 5 (Brutal Realist / "Nagging Spouse") and tap **Activate**.

---

## 🤝 Community Maintenance & Autopilot Governance
This project is a self-sustaining public good. It is not owned by a corporation, and it does not generate profit. 
* **For Users:** The software is free now and will remain free forever.
* **For Developers:** If you wish to contribute to the core ledger logic or expand smart home integrations, please read `CONTRIBUTING.md`. Operational maintenance is overseen by community-appointed Maintainers to ensure the project runs seamlessly without relying on any single individual.
