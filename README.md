
Overview of QbitTalksPDF
This project is inspired by the NotebookLM tool, and implements it with open-source LLMs and text-to-speech models. This tool processes the content of a PDF, generates a natural dialogue suitable for an audio podcast, and outputs it as an MP3 file.

Built with:

Llama 3.3 70B 🦙 via Fireworks AI 🎆 and Instructor 📐
MeloTTS 🐚
Bark 🐶
Jina Reader 🔍
Features
Convert PDF to Podcast: Upload a PDF and convert its content into a podcast dialogue.
Engaging Dialogue: The generated dialogue is designed to be informative and entertaining.
User-friendly Interface: Simple interface using Gradio for easy interaction.
Installation
To set up the project, follow these steps:

Clone the repository:

git clone https://github.com/i-mwangi/QbitTalksPDF
cd QbitTalksPDF
Create a virtual environment and activate it:

python -m venv .venv
source .venv/bin/activate
Install the required packages:

pip install -r requirements.txt
Usage
Set up API Key(s): For this project, I am using LLama 3.3 70B hosted on Fireworks API as its JSON Mode supports passing a pydantic object. So, please set the API key as the FIREWORKS_API_KEY environment variable

Run the application:

python app.py
This will launch a Gradio interface in your web browser.

Upload a PDF: Upload the PDF document you want to convert into a podcast.

Generate Audio: Click the button to start the conversion process. The output will be an MP3 file containing the podcast dialogue.

