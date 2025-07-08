# 📧 Email Writer AI – Chrome Extension

**Email Writer AI** is a productivity-focused Chrome extension that integrates with your email client and uses **Spring AI**, **Gemini API**, and **React** to generate intelligent, context-aware email replies. It places a smart **"AI Write"** button next to the "Send" button in your email composer.

---

## 🚀 Features

- 🧠 **AI-Powered Replies**: Generates smart and context-aware email responses using Google's Gemini API.
- ⚙️ **Spring Boot Backend**: Handles API requests, prompt engineering, and communication with Gemini.
- 💻 **React Frontend**: Injects a seamless UI button in Gmail or other web email clients.
- 📎 **Contextual Awareness**: Automatically reads the current email thread to generate appropriate replies.
- ✏️ **Editable Responses**: Allows users to review and edit AI-generated content before sending.

---

## 🛠️ Tech Stack

| Layer       | Technology                    |
|------------|-------------------------------|
| Backend     | Spring Boot + Spring AI       |
| AI Service  | Gemini API                    |
| Frontend    | React (Chrome Extension)      |
| Build Tool  | Maven                         |
| Styling     | Tailwind CSS (optional)       |
| Deployment  | Chrome Extension Packaging    |

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yushh1718/Email-writer-ai.git
cd Email-writer-ai

```

### 2. Start Spring Boot Backend
``` bash
cd backend
./mvnw spring-boot:run
```
### 3. Configure your Gemini API key in application.properties:
``` bash
spring.ai.gemini.api-key=YOUR_GEMINI_API_KEY
```

### 4. Build React Frontend (Chrome Extension)
``` bash
cd extension
npm install
npm run build
```

### 5. Load Extension in Chrome

- **Open Chrome and go to chrome://extensions/**
- **Enable Developer Mode**
- **Click Load unpacked**
- **Select the extension/build directory**

## 🧠 Future Improvements

- **Add support for multiple email clients (Outlook, Yahoo).**

- **Language translation for international replies.**

- **Smart tone adjustment (formal/informal).**


