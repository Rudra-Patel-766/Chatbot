# 🤖 Chatbot

Interactive AI Chatbot built with React and Vite that allows users to have real-time conversations with an automated chatbot. The application provides a clean user interface, instant responses, loading indicators, and a smooth chatting experience.

## 🚀 Features

### Core Functionality

* 💬 Real-time chatbot conversations
* 👤 User and bot message separation
* 🤖 Automated chatbot responses
* ⌨️ Send messages using Enter key
* ❌ Clear input using Escape key
* 🔄 Loading animation while waiting for responses
* 📜 Automatic scrolling to latest messages
* 🎨 Responsive and modern user interface

### Technical Features

* Built with React 19
* Fast development using Vite
* Component-based architecture
* State management using React Hooks
* CSS styling for responsive design
* Asynchronous API handling
* Modular and maintainable code structure

---

## 📋 Prerequisites

Before running this project, ensure you have:

* Node.js (v18 or higher)
* npm or yarn
* Modern web browser (Chrome, Firefox, Edge)

---

## 🛠️ Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/Rudra-Patel-766/Chatbot.git
cd Chatbot
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

### 4. Open in Browser

```text
http://localhost:5173
```

---

## 📂 Project Structure

```text
Chatbot/
│
├── public/
│   └── vite.svg
│
├── src/
│   ├── assets/
│   │   ├── loading-spinner.gif
│   │   ├── robot.png
│   │   ├── user.png
│   │   └── react.svg
│   │
│   ├── components/
│   │   ├── ChatInput.jsx
│   │   ├── ChatInput.css
│   │   ├── ChatMessage.jsx
│   │   ├── ChatMessage.css
│   │   ├── ChatMessages.jsx
│   │   └── ChatMessages.css
│   │
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
└── README.md
```

---

## 🏗️ Architecture

### Frontend Structure

#### App Component

* Main application component
* Manages overall chatbot layout
* Handles chat state management

#### ChatInput Component

* Captures user input
* Sends messages
* Handles keyboard shortcuts
* Processes chatbot responses

#### ChatMessages Component

* Displays chat conversation
* Automatically scrolls to latest message
* Manages message rendering

#### ChatMessage Component

* Displays individual messages
* Shows user and bot avatars
* Applies message styling

---

## 🔄 Application Workflow

### User Interaction Flow

1. User types a message.
2. Message is added to chat history.
3. Loading spinner is displayed.
4. Chatbot processes the message.
5. Bot response is generated.
6. Response is displayed in the chat window.
7. Chat automatically scrolls to the latest message.

---

## 📸 User Interface Features

### Chat Window

* Clean and responsive design
* Separate styling for user and bot messages
* Easy-to-read conversation layout

### Message Components

* User avatar display
* Robot avatar display
* Message bubbles
* Loading indicators

### Keyboard Shortcuts

| Key    | Action       |
| ------ | ------------ |
| Enter  | Send Message |
| Escape | Clear Input  |

---

## ⚙️ Technologies Used

### Frontend

* React 19
* Vite
* JavaScript (ES6+)
* CSS3

### Development Tools

* npm
* Git
* GitHub

---

## 🚀 Future Enhancements

### Planned Features

* AI-powered responses using OpenAI API
* Dark Mode support
* Chat history storage
* User authentication
* Voice-to-text input
* Text-to-speech responses
* Multi-language support
* Export chat conversations
* Typing indicators
* Mobile application version

---

## 🧪 Testing

### Run Development Mode

```bash
npm run dev
```

### Build Production Version

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push changes

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## 👨‍💻 Author

**Rudra Patel**

GitHub: https://github.com/Rudra-Patel-766

---

## 📝 License

This project is developed for educational and learning purposes.
