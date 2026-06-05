# 🤖 React Chatbot Project

A simple and interactive chatbot application built using **React**, **Vite**, and the **Chatbot API**. The application allows users to send messages and receive automated chatbot responses in real time.

---

## 📌 Features

- Interactive chatbot interface
- Real-time message sending and receiving
- Loading animation while waiting for bot response
- User and bot profile avatars
- Auto-scroll to latest messages
- Keyboard shortcuts:
  - **Enter** → Send message
  - **Escape** → Clear input field
- Responsive and clean UI

---

## 🛠️ Technologies Used

- React 19
- Vite
- JavaScript (ES6+)
- CSS3
- Chatbot API

---

## 📂 Project Structure


Chatbot-main
│
├── public/
│ └── vite.svg
│
├── src/
│ ├── assets/
│ │ ├── loading-spinner.gif
│ │ ├── robot.png
│ │ ├── user.png
│ │ └── react.svg
│ │
│ ├── components/
│ │ ├── ChatInput.jsx
│ │ ├── ChatInput.css
│ │ ├── ChatMessage.jsx
│ │ ├── ChatMessage.css
│ │ ├── ChatMessages.jsx
│ │ └── ChatMessages.css
│ │
│ ├── App.jsx
│ ├── App.css
│ ├── main.jsx
│ └── index.css
│
├── package.json
├── vite.config.js
└── README.md


---

## 🚀 Installation

### 1. Clone the Repository

```bash
    git clone https://github.com/Rudra-Patel-766/Chatbot.git
2. Navigate to Project Directory
    cd Chatbot
3. Install Dependencies
    npm install
4. Start Development Server
    npm run dev

The application will be available at:
http://localhost:5173

📖 How It Works

User enters a message in the input box.
Message is added to the chat window.
A loading spinner is displayed while waiting for a response.
The chatbot generates a response using:
Chatbot.getResponseAsync()
The chatbot response is displayed in the conversation.
The chat window automatically scrolls to the newest message.

🎯 Components:

ChatInput

Responsible for:

Capturing user input
Sending messages
Handling Enter and Escape keys
Fetching chatbot responses

ChatMessages

Responsible for:

Displaying all chat messages
Auto-scrolling to the latest message

ChatMessage

Responsible for:

Rendering individual messages
Displaying user and chatbot avatars

📸 User Interface

The application contains:

Welcome message on startup
User message bubbles
Chatbot message bubbles
User profile icon
Robot profile icon
Loading animation