<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,240,255,10,25,47&height=220&section=header&text=Shono%20AI%20(শোনো%20এআই)%20🎙️&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=38&desc=The%20Unlimited%20Bangladeshi%20Dialect%20Jarvis%20%26%20Interactive%20HUD&descFontSize=18&descAlignY=62" width="100%"/>

  [![Web Speech API](https://img.shields.io/badge/Web_Speech_API-Streaming_STT-00f0ff?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-Cyberpunk_HUD-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![Gemini Flash](https://img.shields.io/badge/Google-Gemini_Flash-8E75C2?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
  [![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
</div>

---

# 🎙️ Shono AI (শোনো এআই) // The Unlimited Bangladeshi Jarvis
> **Bangladeshi Dialect-Aware Acoustic Pipeline, Architectural Blueprint & Futuristic HUD Interface**

"Shono AI" is designed as the first voice assistant engineered to understand and fluently converse across all major regional dialects of Bangladesh (Sylheti, Chatgaya, Noakhailla, Barisailla, Rangpuri, Dhakaiya, and Standard Bengali) as well as English.

---

## 🌌 System Architecture

```mermaid
graph TD
    User([User Voice Input]) --> Mobile[Android Floating Bubble / Web App]
    User --> WA[WhatsApp Voice Bot]
    User --> FB[Messenger Bot]
    
    Mobile --> Gateway[FastAPI / Node.js Streaming Gateway]
    WA --> Gateway
    FB --> Gateway
    
    Gateway --> STT[Dialect-Aware Acoustic Pipeline]
    STT --> Brain[Gemini Flash Engine]
    Brain --> IntentEngine[Action Dispatcher]
    
    IntentEngine --> Actions[Phone Call / WhatsApp / Alarms / Media / Desktop]
```

---

## 🎨 Interactive Cyberpunk HUD Features

* **3D Audio Visualizer Orbit:** Circular real-time soundwave reacting to vocal input.
* **Dialect Classifier Visualizer:** Visual badges indicating detected regional accent and language nuance.
* **Instant Action Widgets:** Quick cards for weather, news, system diagnostics, and communication shortcuts.

---

## ⚡ Quick Start

Simply clone the repository and open `index.html` in any modern web browser to experience the interactive HUD.

```bash
git clone https://github.com/monisharani333022-eng/Shono-AI-Bangladeshi-Jarvis.git
cd Shono-AI-Bangladeshi-Jarvis
# Open index.html in your browser
```

---

## 👤 Author

* **Developer:** [Jubayer Ahmad](https://github.com/monisharani333022-eng)
* **Email:** [monisharani333022@gmail.com](mailto:monisharani333022@gmail.com)
* **Location:** Dhaka, Bangladesh 🇧🇩

---

## 📄 License

Distributed under the MIT License.
