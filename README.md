# 🤖 OSB - Open Source Bot

**OSB (Open Source Bot)** is a lightweight, customizable AI chatbot interface designed for developers and researchers who want a beautiful front-end to interact with local or remote language models. The interface is built using HTML, CSS, and JavaScript, with additional tools for model management, conversation logging, and chat styling.

---
## Aplication Setup
To setup the aplciation into the a androind device follow the instruction [here](https://open-source-bot.blogspot.com).

You must need to download the following tools to run the `frontend/OSB.html` in a android device. You can get them from Google Play Store:
- [Turmux](https://termux.dev/en/)
- [Ollama](https://ollama.com) in turmux (`pkg install ollama`)
- [Simple HTTP Server](https://play.google.com/store/apps/details?id=com.phlox.simpleserver&hl=en)

## 🌟 Features

### 🧠 AI Model Selector
- Easily switch between different AI models using a dynamic model selector input.
- Default support for multiple models (e.g., `gemma3:4b`, `qwen3:1.7b`, etc.).
- Change the default model and manage model preferences through a dedicated management page.

### 💬 Chat Interface
- Clean, responsive, and mobile-friendly chat UI.
- Messages are styled with clear differentiation between **incoming** and **outgoing** responses.
- Built-in support for **text**, **images**, and **user annotations** (highlight, underline).

### 🛠️ Toolbar Actions
- **Model Management** (`O` button): Open the model management panel to edit or add models.
- **Dark Mode Toggle** (`🔅`): Switch between light and dark themes.
- **Save Conversation** (`💾`): Save your current chat as a PDF using `jsPDF` + `html2canvas`.
- **Reload Page** (`🔄`): Reload the chat UI quickly.
- **Highlighter Tool** (`🖍️`): Highlight parts of your messages.
- **Underline Tool** (`✏️`): Underline important text.
- **Eraser Tool** (`⬜`): Remove formatting (highlight or underline) from selected messages.

### 📸 Camera & Image Support
- Insert images or take pictures directly within the chat using the camera button.
- Includes modal views for camera preview and image annotation before sending.

### 🧩 Model Management Page
- Add or remove custom models.
- Set and visualize the current default model.
- View pull status and progress of model updates.

---
