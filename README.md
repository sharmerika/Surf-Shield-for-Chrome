# SurfShield for Chrome

SurfShield is a Chrome-native AI assistant that helps users detect phishing and scam messages directly in their browser. Built with Gemini Nano and Chrome Prompt API, it empowers users with real-time analysis, educational feedback, and reporting tools.

---

##  Features

- **Phishing Detection**: Flags suspicious messages using on-device AI
- **Explainer Block**: Shows *why* a message is suspicious
- **Report Button**: Lets users log flagged messages
- **Sidepanel UI**: Seamless experience inside Chrome
- **Dataset Injection**: Uses known phishing URLs for tailored analysis

---

##  Tech Stack

- Chrome Prompt AI Demo (Manifest v3)
- Gemini Nano (on-device AI)
- VS Code
- JSON dataset for phishing patterns
- `marked` + `DOMPurify` for clean markdown rendering

---

##  Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/sharmerika/Surf-Shield-for-Chrome.git
2. 	Run the build:
   npm install
   npm run build

3. Open Chrome and go to chrome://extensions
4. Enable Developer Mode
5. Click Load unpacked and select the project folder

## Testing Instructions
- Open the SurfShield sidepanel
- Type a suspicious message (e.g., “Click this screenshot to verify your account”)
- Click Run
- Review the assistant’s response and explanation
- If flagged, click Report this
- Adjust Temperature and Top-k sliders to modify AI behavior
- Use Reset to restart the session

## Demo Video
Watch the walkthrough here: [SurfShield Demo](https://youtu.be/B_0_hc2AqXM)

## Inspiration
SurfShield was inspired by the need to protect elderly users, people with disabilities, and anyone who may not be tech-savvy. It acts as a buffer between users and potential threats, helping them pause and think before reacting. The goal is to empower users with clarity, not just detection.

## What’s Next
- Localization for Filipino, Hiligaynon, and other languages
- Mobile app version for cross-platform protection
- Public reporting dashboard for community-driven safety
---



