🤖 Multi-Model AI Chat Assistant
A powerful, privacy-focused, 100% client-side AI chat interface with multi-model support and an intelligent question queue. Chat with top AI models like Gemini, GPT, and Claude in a single, secure web application that runs entirely in your browser.

✨ Live Demo (Coming Soon)
🚀 Key Features
🧠 Multi-Model Support: Seamlessly switch between top AI models from Google (Gemini), OpenAI (GPT), Anthropic (Claude), Meta (Llama), Mistral, or even connect to your own custom API endpoints.

🔐 Secure & Private: Your conversations and API keys never leave your browser. All data is stored locally in localStorage, and API calls are made directly from your client to the AI provider, ensuring complete privacy.

⚡ Intelligent Question Queue: Don't wait for one answer to finish before asking your next question. The app intelligently queues your prompts and processes them sequentially, with a clear view of what's coming up next.

🎙️ Voice-to-Text Input: Use your voice to ask questions. The assistant features a hands-free mode with high-quality speech recognition, perfect for multitasking.

📱 Fully Responsive Design: Enjoy a seamless experience on any device. The interface is beautifully designed to work on desktops, tablets, and mobile phones.

🌐 Zero Backend - Runs Anywhere: This is a single index.html file with no server-side dependencies. You can run it locally by simply opening the file or host it on any static web hosting service (like GitHub Pages, Vercel, or Netlify) for free.

💡 Real-time Feedback: The UI provides a dynamic experience with typing indicators, status updates, and toast notifications for a modern chat feel.

🛠️ How It Works
This application is built with simplicity and security as top priorities. It's a testament to the power of modern web browsers.

Client-Side Logic: The entire application is powered by vanilla JavaScript (ES6+), HTML5, and CSS3. There is no backend server, no database, and no build process required.

Local Storage for Keys: When you save an API key for a model, it is stored in your browser's localStorage. This data is persistent on your device but is never transmitted over the network to our servers (because we don't have any!).

Direct API Communication: When you send a message, the JavaScript code constructs an API request and sends it directly from your browser to the selected AI provider's public API (e.g., https://api.openai.com/...).

This architecture makes the app incredibly secure, private, and easy to deploy.

▶️ Getting Started
Get your own copy of the AI Assistant up and running in under a minute.

Prerequisites
A modern web browser (Chrome, Firefox, Edge, etc.).

API keys for the AI models you wish to use. You can get these from:

Google AI Studio for Gemini models.

OpenAI Platform for GPT models.

Anthropic Console for Claude models.

Installation
Download the Code
Clone the repository or simply download the index.html file to your local machine.

Bash

git clone https://github.com/your-username/ai-chat-assistant.git
cd ai-chat-assistant
Run the Application
Simply open the index.html file in your web browser.

Pro Tip: For the best experience and to enable the voice recognition feature (which requires a secure https context), it's recommended to serve the file with a local web server. If you have Python installed, you can easily do this:

Bash

# For Python 3
python -m http.server
Then, navigate to http://localhost:8000 in your browser.

Configure Your API Key

In the sidebar, select your desired AI model from the dropdown menu.

Enter your personal API key into the "Enter your API key" field.

Click "Save API Key". A notification will confirm that it's saved.

Start Chatting!
The message input field will become active. You can now type or use the microphone to start your conversation with the AI.

🤖 Supported Models
The assistant is configured to work with the following models out-of-the-box:

Google: Gemini Pro, Gemini 1.5 Flash, Gemini 1.5 Pro

OpenAI: GPT-3.5 Turbo, GPT-4

Anthropic: Claude 3 Sonnet, Claude 3 Opus

Meta: Llama 2, Llama 3 (requires a self-hosted endpoint)

Mistral AI

Custom API: Connect to any API that follows a similar request/response structure.

💻 Technology Stack
HTML5

CSS3 (with CSS Variables for easy theming)

Vanilla JavaScript (ES6+)

Font Awesome (for icons)

Google Fonts (for typography)

📜 License
This project is licensed under the MIT License. See the LICENSE file for details. You are free to use, modify, and distribute this project as you see fit.
