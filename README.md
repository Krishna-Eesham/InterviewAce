🎙️ InterviewAce - AI Interview Copilot

License: MITHTML5JavaScript


InterviewAce is a standalone, browser-based AI assistant designed to help you ace your next job interview. It features real-time voice transcription, intelligent answer generation via LLMs (OpenAI, Anthropic, Google), and an ATS-friendly multi-resume builder.


⚠️ Note: This tool is designed for practice and preparation. Using live AI assistance during an actual interview may violate the terms of the interview process. Use responsibly.


✨ Features

🎯 Live Interview Copilot
Voice-to-Text: Uses the Web Speech API to transcribe interview questions in real-time.
AI Responses: Generates professional answers using the STAR method (Situation, Task, Action, Result).
Context Awareness: Upload your Resume and Job Description (JD) to tailor answers specifically to the role.
Stealth Mode: Reduces interface opacity and allows quick hiding (ESC key) for subtle use.
Multi-Provider Support: Switch between OpenAI (GPT-4), Anthropic (Claude), and Google (Gemini).

📄 Multi-Resume Generator
Voice Input: Describe your background via microphone to generate resume content.
ATS-Friendly Designs: Choose from 5 professional, optimized templates.
Multiple Variations: Generate up to 10 different resume versions focusing on different skills (Leadership, Technical, etc.).

🔒 Privacy & Security
Local Storage: All data (API keys, context, history) is stored in your browser's localStorage.
Direct API Calls: Requests are sent directly from your browser to the AI provider. No intermediate servers collect your data.

🚀 Quick Start
No backend installation required. This is a single-file application.

Download: Save the code as index.html.

Open: Drag and drop the file into Chrome, Edge, or Safari.

Microphone: Allow microphone permissions when prompted (required for voice features).

Important: For voice recognition to work on a deployed website (not just file://), the site must be served over HTTPS or localhost.

⚙️ Configuration
To use the AI features, you must configure your API keys within the app.

Open the application in your browser.
Click the ⚙️ (Settings) icon in the top-right navigation.

Select Provider: Choose between OpenAI, Anthropic, or Google.

Enter API Key: Paste your API key.

The key is saved locally in your browser and never sent to our servers.

Save: Click "Save Settings".

Where to get API Keys?

OpenAI: platform.openai.com

Anthropic: console.anthropic.com

Google AI: makersuite.google.com

📖 Usage Guide

1. Using the Live Copilot
Navigate to the Live Copilot tab.
Click Listening: OFF to activate voice recognition.
Ask a question (or type it in the input box).
The AI will generate a response and display it at the top of the conversation area.
Context: Click the Context button to paste your Resume and the Job Description. The AI will use this to customize future answers.

2. Building Resumes
Navigate to the Resume Builder tab.
Click the Microphone icon and speak your professional background, or type it in the text area.
Select the Number of Variations and Target Role.
Click Generate ATS-Friendly Resumes.
View the generated designs and click Download PDF (simulated in demo).

3. Stealth Mode
Click the Stealth: OFF button in the Copilot header.
The interface opacity will drop to 30%.
Press ESC at any time to quickly navigate back to the Home page.

🛠️ Tech Stack
Core: HTML5, CSS3, Vanilla JavaScript (ES6+).
Styling: CSS Variables, Flexbox, Grid, Animations.
Icons: Font Awesome 6.4.
Fonts: Google Fonts (Syne, Space Mono).
Speech: Web Speech API (webkitSpeechRecognition).
AI: Fetch API integration with OpenAI, Anthropic, and Google endpoints.

🌐 Browser Compatibility
Feature	Chrome	Edge	Safari	Firefox
Core UI	✅	✅	✅	✅
Voice Input	✅	✅	✅	❌*
Resume Print	✅	✅	✅	✅
*Firefox requires configuration flags for Web Speech API.

📂 Project Structure
The application is contained entirely within index.html.

<style>: All CSS including responsive design and animations.
<body>: Semantic HTML structure for Home, Copilot, and Resume sections.
<script>: Application logic, state management, API handlers, and UI controllers.

  🗺️ Roadmap
 Add PDF generation (using jspdf or html2pdf).
 Support for more languages in voice recognition.
 Dark/Light theme toggle.
 Local database (IndexedDB) for saving chat history longer term.
 Export Chat History to text/markdown.

  ⚠️ Disclaimer
This tool is provided "as is" for educational and practice purposes. The developers are not responsible for the outcomes of any job interviews where this tool is used. Always verify the accuracy of AI-generated responses.

📝 License
This project is open source and available under the MIT License.

🤝 Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
