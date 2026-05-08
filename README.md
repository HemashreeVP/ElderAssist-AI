# 👵 ElderAssist AI

ElderAssist AI is a senior-friendly AI assistant that helps elderly users understand documents, detect scams, extract reminders, and listen to simplified explanations using voice support.

---

# 📌 Problem

Senior citizens often struggle with:

- Scam SMS messages
- Fake bank alerts
- Phishing links
- Confusing bills and prescriptions
- Small text and difficult wording
- Remembering appointments and events

Many elderly users are vulnerable to:
- OTP scams
- Fraudulent payment requests
- Fake delivery messages
- Suspicious verification links

Existing tools are often:
- difficult to use
- too technical
- not accessibility-friendly
- lacking voice assistance

---

# 💡 Solution

ElderAssist AI simplifies documents and alerts for elderly users.

The application can:
- Scan or upload documents/photos
- Analyze typed messages
- Analyze spoken voice input
- Detect possible scams
- Explain content in simple language
- Extract dates and times
- Create reminder cards
- Read results aloud

The UI is designed specifically for seniors using:
- Large buttons
- High readability
- Clear warnings
- Simple workflows

---

# ✨ Features

## 📷 Document Scanning
Analyze:
- Bills
- Prescriptions
- Invitations
- Delivery updates
- Scam screenshots
- Bank messages

---

## 🚨 Scam Detection
Detects:
- Phishing links
- OTP scams
- Fake bank alerts
- Urgent payment requests
- Suspicious verification messages

---

## 🎤 Voice Input
Users can:
- Record voice messages
- Speak reminders/events
- Analyze spoken content

---

## 🔊 Read Aloud
Reads analysis results aloud for elderly accessibility.

---

## 📅 Reminder Extraction
Automatically extracts:
- Dates
- Times
- Events
- Appointments

and generates reminder cards.

---

# 🛠️ Tech Stack

## Frontend
- Gradio

## Backend
- Python

## AI / APIs
- Google Gemini API

## OCR
- Tesseract OCR
- OpenCV

## Speech
- SpeechRecognition
- Browser Speech Synthesis API

---

# ⚙️ Setup

## 1️⃣ Clone Repository

```bash
git clone <https://github.com/HemashreeVP/ElderAssist-AI>
cd ElderAssist-AI
```

## 2️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Install Tesseract OCR

### Google Colab / Linux

```bash
apt-get -y install tesseract-ocr
```

### Windows

Install Tesseract OCR from:
https://github.com/UB-Mannheim/tesseract/wiki

---

## 4️⃣ Add Gemini API Key

Replace:

```python
genai.configure(api_key="YOUR_API_KEY")
```

with your Gemini API key.

---

## 5️⃣ Run the Project

### Jupyter Notebook

Open:

```text
ElderAssistAI.ipynb
```

Run all cells.

---

# 🌐 Supported Languages

- English
- Kannada
- Hindi

---

# 👥 Target Users

- Senior citizens
- Elderly smartphone users
- Users with limited digital literacy
- Regional language users

---

# 📌 Use Cases

- Detecting scam SMS messages
- Understanding prescriptions
- Reading bank alerts
- Appointment reminders
- Delivery message analysis

---

# 🚀 Future Enhancements

- More Indian language support
- Offline AI support
- Emergency contact alerts
- WhatsApp integration
- Medicine reminder notifications

---

# 📄 AI Disclosure

This project uses:
- Google Gemini API
- OCR technologies
- Speech recognition
- AI-assisted development tools

for educational and research purposes.

---

# 📹 Demo Video

Add your demo video link here:

```text
https://drive.google.com/file/d/1_3ChizxJ4Mjdnla8e41W0k5_4jhQ7fjI/view?usp=sharing
```

---

# 📜 License

MIT License

# 👩‍💻 Team

Team Name: MS Ramaiah Institute of Technology_Comet

Project developed for Samsung PRISM – Clash of the Claws.
