<h1 align="center"> Vision ✨</h1>

**AI-powered real-time voice & document chat assistant**

[🌐 Watch Live](https://vision-virid.vercel.app/)

## Overview

**Vision** is a smart and responsive AI assistant that enables users to interact through **voice**, **text**, and **documents**. Built with Flutter and Dart, Vision provides a seamless user experience with real-time voice recognition, dynamic chat rendering, and document-based query support.

Whether you’re looking to summarize PDFs, chat with context, or speak to AI hands-free — Vision does it all in one intuitive interface.

---

## ✨ Features

- 🎤 **Voice Input**: Speak to the assistant using the built-in voice recognition.
- 📄 **Document Upload**: Upload PDFs and ask questions based on the content.
- 💬 **Conversational Chat**: Persistent chat sessions powered by large language models (Groq/LLM).
- 🖥️ **Responsive UI**: Works on both mobile and web via Flutter.
- 📦 **Session Storage**: Previous sessions can be stored and retrieved locally.

---

## 📁 Project Structure

```bash
lib/
├── main.dart                         # App entry point
├── models/                           # Data models for message and chat session
│   ├── message.dart
│   └── chat_session.dart
├── services/                         # Logic for AI, voice, and storage handling
│   ├── groq_service.dart
│   ├── voice_service.dart
│   └── storage_service.dart
├── providers/                        # State management using Provider
│   └── chat_provider.dart
├── screens/                          # UI screens for home and chat
│   ├── home_screen.dart
│   └── chat_screen.dart
├── widgets/                          # Reusable UI components
│   ├── message_bubble.dart
│   ├── chat_input.dart
│   ├── voice_button.dart
│   └── document_picker.dart
└── utils/                            # Theme and constants
    ├── theme.dart
    └── constants.dart
```

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK installed (>= 3.10.0)
- Dart enabled IDE (VSCode / Android Studio)

### Installation

```bash
git clone https://github.com/yourusername/vision.git
cd vision
flutter pub get
flutter run -d chrome   # or your desired device
```

---

## 🔧 Configuration

- Configure API keys (Groq, voice services, etc.) in a `.env` or `constants.dart` file.
- Firebase or local storage configuration for session management.

---

## 📸 Screenshots

![Image](https://github.com/user-attachments/assets/5114ac1e-1207-4790-9f1a-b0b68e12c0f5)

![Image](https://github.com/user-attachments/assets/c00b7a27-fdd9-4898-8626-a6d0efc81e5e)
