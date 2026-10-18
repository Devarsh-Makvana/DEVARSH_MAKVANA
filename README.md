
# Devarsh

# 🛡️ CyberShield X — AI for Good

**CyberShield X** is an interactive, educational cyber-safety demonstration platform and exhibition dashboard. Built as a student cyber-safety project, it showcases how AI can be leveraged as an explanation and learning aid to turn complicated digital security topics into understandable guidance, helping users build safer online habits.

---

## ✨ Features

- **🤖 Hybrid AI Control Center**: Seamlessly switches between online Gemini AI (using your own API key kept securely in memory) and a built-in Offline AI mode when internet/keys are unavailable.
- **🧠 AI Cyber Assistant & Message Explainer**: Translates technical warning signs from suspicious texts or phishing attempts into plain language.
- **🔬 Interactive Safety Labs**: Features dedicated modules including an **Email Lab**, **QR Lab**, **Social Lab**, and **Device Lab** to analyze risky digital patterns locally.
- **🚀 Advanced Exhibition Dashboard**: Tracking engine for user learning analytics, progress metrics, and an Achievement Center with badges.
- **🆕 Real-World Safety Toolkit**: Includes a browser-based local **File Integrity Lab (SHA-256 calculator)** and a **Privacy Data Detector** to scan text for sensitive information before sharing it online.
- **🎯 Interactive Cyber Decision Simulator**: Gamified scenarios teaching the 5-step Exhibition Story Mode: *Notice, Pause, Verify, Protect, and Learn*.

## 🚀 Tech Stack

- **Frontend / Core:** HTML5, CSS3, JavaScript (ES6+)
- **AI Integration:** Gemini API (Online Mode) & Local Fallback Heuristics (Offline Mode)
- **Security Processing:** Crypto Web API (for local SHA-256 fingerprinting)

## 🛠️ Installation & Setup

Since this project runs locally and processes data inside the browser, setting it up is incredibly simple:

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, or Safari).
- (Optional) A Gemini API key to unlock online AI assistance features.

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com<your-username>/cybershield-x.git
   cd cybershield-x
   ```

2. **Launch the application:**
   Simply open the `index.html` file directly in your favorite web browser, or use a local development server like Live Server in VS Code:
   ```bash
   # Optional: If using python to host locally
   python -m http.server 8000
   ```
   Open `http://localhost:8000` in your browser.

## 🎯 How to Use the Demo

1. **Set up AI:** Paste your optional Gemini API key into the control center panel to activate online mode, or proceed directly with the built-in **Offline AI**.
2. **Explore the Labs:** Try running the **OTP or Phishing examples** in the AI Cyber Assistant, or paste a fake suspicious message to watch the AI break down warning signs.
3. **Take the Mega Quiz:** Put your knowledge to the test in the built-in 5-question safety quiz and view your real-time Exhibition Impact Score.


## 📄 License

Distributed under the **MIT License**. See the `LICENSE` file for details.

---
👨‍💻 **Developed by** [@Devarsh Makvana](https://github.com<Devarsh>) 