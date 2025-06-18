✨ ExamCao

ExamCao is a modern web application suite designed to enhance document processing and text readability. It includes two powerful components:

🎯 ExamCao Web App – A browser-based tool powered by Groq AI for summarizing, translating, and narrating documents.

🔤 Bionic Hindi Text Converter – A Streamlit app that transforms Hindi (Devanagari) text into a "bionic" format for better readability.

Both components are responsive, user-friendly, and privacy-focused, ensuring a seamless experience across all devices.

📚 Table of Contents
✨ Features

🚀 Installation

🛠️ Usage

🎨 Customization Options

🧪 Technologies Used

📂 Project Structure

🤝 Contributing

🐞 Issues

📄 License

📬 Contact

✨ Features
✅ ExamCao Web App
🔁 Smart Upload: Drag-and-drop support for PDF, TXT, and DOCX files.

🧠 AI Summarization: Highlights key insights using advanced AI with optional bionic formatting.

🌐 Multilingual Support: Translate and summarize in over 12 languages with native font rendering.

🗣️ Natural Voice Narration: High-quality TTS in various accents.

📤 Smart Export: Export summaries as PDFs or PPTs (Coming Soon).

🔒 Privacy First: All processing happens locally in your browser.

⚡ Lightning Fast: Instant file handling with no server delays.

📱 Responsive Design: Optimized UI for all devices.

🔤 Bionic Hindi Text Converter
🧬 Text-to-Bionic Hindi Conversion: Enhances Hindi text for better reading.

🎛️ Custom Emphasis Settings: Tweak emphasis levels as per your comfort.

🌙 Dark/Light Theme Support: View comfortably in any lighting.

🔠 Adjustable Font Size: Set text size to match your needs.

🎧 Coming Soon:

Text-to-speech playback

Document upload

Voice input

🚀 Installation
🖥️ ExamCao Web App (No Backend Needed)
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/examcao.git
cd examcao
Serve the Application Locally

Using Python:

bash
Copy
Edit
python -m http.server 8000
# Visit http://localhost:8000 in your browser
Using Node.js:

bash
Copy
Edit
npm install -g http-server
http-server
# Visit http://localhost:8080
Dependencies? None! Uses Tailwind via CDN + vanilla JS.

🧪 Bionic Hindi Text Converter (Streamlit App)
Clone the Repository (if not already done)

bash
Copy
Edit
git clone https://github.com/your-username/examcao.git
cd examcao
Install Requirements
Python 3.8+ is needed.

bash
Copy
Edit
pip install -r requirements.txt
If requirements.txt is missing, start with:

bash
Copy
Edit
pip install streamlit
(Optional future features may use gTTS, pyttsx3, PyPDF2, python-docx)

Run the App

bash
Copy
Edit
streamlit run app.py
Navigate to http://localhost:8501

🛠️ Usage
📄 ExamCao Web App
Launch the App: Open index.html in your browser.

Explore the Interface: Browse through features and click Get Started Free.

Upload and Process File:

Choose a language

Upload .pdf, .txt, or .docx

Click Process File

Interact:

Read or listen to the summary

Use Download Summary to save as .txt

Future: Export as PDF/PPT with enhanced formatting.

🧬 Bionic Hindi Text Converter
Run the Streamlit App

bash
Copy
Edit
streamlit run app.py
Enter Text & Customize:

📝 Paste Hindi (Devanagari) text

🔧 Adjust:

Emphasis Level

Color

Theme

Font Size

View Output Instantly

Coming Soon:

🎧 TTS support

📄 File Upload

🎙️ Voice Input

🎨 Customization Options (Bionic Hindi)
Option	Description
Emphasis Level	Adjust word highlight ratio
Emphasis Color	Pick a color to emphasize words
Theme	Switch between dark and light modes
Font Size	Scale text size for accessibility

🧪 Technologies Used
💻 ExamCao Web App
HTML5

Tailwind CSS (via CDN)

JavaScript (Vanilla)

SVG Icons

No Backend = Full Client-Side Privacy

🐍 Bionic Hindi Text Converter
Python 3.8+

Streamlit

(Optional: gTTS, pyttsx3, PyPDF2, python-docx)

📂 Project Structure
bash
Copy
Edit
examcao/
├── index.html              # Web App entry point
├── app.py                  # Streamlit app
├── /assets                 # CSS, JS, Icons
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
🤝 Contributing
Contributions are welcome for both apps! 🎉

Fork the Repo

Create a Branch

bash
Copy
Edit
git checkout -b feature/your-feature-name
Make Changes:

Web App: Tailwind + JS

Streamlit: Python

Test Locally

Push & PR

bash
Copy
Edit
git commit -m "Describe your changes"
git push origin feature/your-feature-name
Open a Pull Request

🐞 Issues
Found a bug? Have a feature request?
Open an issue.

📄 License
This project is licensed under the MIT License.
