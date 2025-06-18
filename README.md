ExamCao
ExamCao is a modern web application suite designed to enhance document processing and text readability. It consists of two main components:

ExamCao Web App: A browser-based application powered by Groq AI that summarizes, translates, and presents documents (PDF, TXT, DOCX) with features like multilingual summarization, natural voice narration, and smart export options.
Bionic Hindi Text Converter: A Streamlit web application that transforms Hindi (Devanagari) text into "bionic Hindi" text to improve readability and comprehension.

Both components are designed to be responsive, user-friendly, and privacy-focused, ensuring a seamless experience across all screen sizes.
Features
ExamCao Web App

Smart Upload: Drag-and-drop support for PDF, TXT, and DOCX files with instant processing.
AI Summarization: Extracts key insights using advanced AI, with bionic reading for enhanced comprehension.
Multilingual Support: Summarize and translate documents in over 12 languages with accurate translations and native font rendering.
Natural Voice Narration: High-quality text-to-speech in multiple accents for listening to summaries.
Smart Export: Export summaries as polished presentations in PDF or PPT formats.
Privacy First: Local, in-browser processing ensures your files remain secure with no data leaving your device.
Lightning Fast: Instant file processing without server delays, regardless of file size.
Responsive Design: Fully responsive UI that adapts to all screen sizes, from mobile to desktop.

Bionic Hindi Text Converter

Text-to-Bionic Hindi Conversion: Transforms Hindi (Devanagari) text into bionic format for enhanced readability.
Customizable Emphasis Settings: Adjust the level of word emphasis to suit user preferences.
Dark/Light Theme Support: Switch between dark and light modes for comfortable viewing.
Adjustable Font Size: Customize text size for better readability.
Text-to-Speech Capability: Coming soon.
Document Upload Support: Coming soon.
Voice Input Support: Coming soon.

Installation
ExamCao Web App
The web app is a static application that requires no backend setup.

Clone the Repository:
git clone https://github.com/your-username/examcao.git
cd examcao


Serve the Application: Use a local server to serve the static files:

Using Python (Python 3.x required):
python -m http.server 8000

Open your browser and navigate to http://localhost:8000.

Using Node.js (requires npm): Install a simple server like http-server:
npm install -g http-server
http-server

Open your browser and navigate to http://localhost:8080.



No Dependencies Required: The web app uses Tailwind CSS via CDN and vanilla JavaScript, so no additional dependencies are needed.


Bionic Hindi Text Converter
The Streamlit app requires Python and specific dependencies.

Clone the Repository (if not already done):
git clone https://github.com/your-username/examcao.git
cd examcao


Install Dependencies: Ensure you have Python 3.8+ installed, then install the required packages:
pip install -r requirements.txt

Note: If the requirements.txt file is not yet created, typical dependencies for a Streamlit app might include:
streamlit

Additional dependencies may be required for text-to-speech or document processing features (to be added when implemented).

Run the Streamlit App:
streamlit run app.py

Open your browser and navigate to the URL provided by Streamlit (typically http://localhost:8501).


Usage
ExamCao Web App

Open the Application: Access the application by opening index.html in a modern web browser (Chrome, Firefox, Safari, Edge).

Navigate the Landing Page:

Explore the features, testimonials, and "How It Works" sections.
Click "Get Started Free" to access the file processing section.


Process a File:

Select a language from the dropdown (e.g., English, Spanish, French).
Drag and drop or browse to upload a PDF, TXT, or DOCX file.
Click "Process File" to generate a summary (simulated with sample content in this demo).
View the summary, listen to it, or download it as a text file.


Export Options:

Use the "Download Summary" button to save the summary as a .txt file.
(Future implementation: Export as PDF or PPT presentations.)



Bionic Hindi Text Converter

Run the Streamlit App: After starting the app with streamlit run app.py, access it via the provided URL (e.g., http://localhost:8501).

Convert Hindi Text:

Input Hindi (Devanagari) text into the provided text area.
Adjust settings:
Emphasis Level: Control how much of each word is emphasized.
Color: Choose the emphasis color for bionic text.
Theme: Switch between dark and light modes.
Font Size: Adjust text size for readability.


View the converted bionic Hindi text instantly.


Future Features (Coming Soon):

Use text-to-speech to listen to the bionic text.
Upload documents for automatic text extraction.
Use voice input to enter text.



Customization Options (Bionic Hindi Text Converter)

Emphasis Level: Adjust the portion of each word highlighted to optimize readability.
Color: Select a color for the emphasized text to enhance visual distinction.
Theme: Choose between dark and light modes for better user comfort.
Font Size: Modify text size to suit different screen sizes and user preferences.

Technologies Used
ExamCao Web App

HTML5: For structuring the web application.
Tailwind CSS: For responsive and modern styling via CDN.
JavaScript: For interactivity, file handling simulation, and summary generation.
SVG Icons: For visual elements and icons.
No Backend: Purely client-side processing for privacy and speed.

Bionic Hindi Text Converter

Python: Core language for the Streamlit application.
Streamlit: Framework for building the interactive web interface.
(Future Dependencies): Libraries for text-to-speech (e.g., gTTS, pyttsx3) and document processing (e.g., PyPDF2, python-docx) may be added.



