# 🧠 Voice-based Doctor-Patient Simulation

This project is a **voice-interactive AI simulation** between a doctor and a patient using OpenAI's GPT and TTS models with Gradio. It demonstrates real-time speech-to-text and text-to-speech interactions, simulating a healthcare consultation experience.

---

## 📁 Project Structure
├── gradio_app.py # Main Gradio UI and interaction loop
├── voice_of_the_doctor.py # Doctor's voice synthesis (OpenAI TTS)
├── voice_of_pateint.py # Patient's voice synthesis (OpenAI TTS)
├── brain_of_the_doctor.py # LLM logic for the doctor's responses


---

## 🚀 Features

- 🎙️ Real-time voice input using Gradio  
- 🗣️ Voice output for both doctor and patient using OpenAI TTS (`tts-1-hd`)  
- 🧠 LLM-powered responses from the "doctor" (e.g., GPT-4 or GPT-4o)  
- 🔁 Turn-based voice conversation between two AI agents  
- 🌐 Web-based interface via Gradio  

---

## 🩺 Use Cases

- AI medical assistant simulation  
- Doctor-patient roleplay for training purposes  
- Conversational AI demo in healthcare  
- Multi-agent system development starter  

---

## ⚙️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/voice-doctor-ai.git
cd voice-doctor-ai
pip install -r requirements.txt
```

Set your OpenAI API key:
``` bash
export OPENAI_API_KEY=your_openai_key
```


💡 How It Works

gradio_app.py connects the voice modules and brain logic into a seamless UI.
voice_of_the_doctor.py converts the doctor's text response to realistic speech.
voice_of_pateint.py converts the patient’s text input to speech (or can be extended for automated LLM input).
brain_of_the_doctor.py sends input to the GPT model and returns a medically-informed response.

▶️ Run the App

Start the Gradio interface:
```
python gradio_app.py
```

📦 Requirements

Python 3.9+
openai
gradio
soundfile
numpy
Any additional dependencies listed in requirements.txt


