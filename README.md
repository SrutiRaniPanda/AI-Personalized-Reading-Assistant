# AI-Personalized-Reading-Assistant

# 📖 AI-Powered Personalized Reading Assistant

An intelligent reading assistant designed to enhance reading comprehension, vocabulary building, and engagement through NLP, gamification, and interactive features.

---

## 🚀 Features Implemented

### 1. 📄 Article Loading & Text Processing
- Load articles from text files or paste text directly.
- Analyze text using **spaCy** and **NLTK** for NLP processing.

### 2. 🧠 Difficult Word Identification & Simplification
- Automatically detects difficult words (>7 characters or rare words).
- Highlights words in **yellow** (moderate) and **red** (hard).
- Toggle between original and simplified version.
- Built-in simplification database for easy reading.

### 3. 📚 Interactive Word Learning
- Click on words to hear pronunciation and view definitions.
- Displays word type, simplified form, and meaning.
- Uses **pyttsx3** for offline text-to-speech.

### 4. 🔊 Read-Aloud Feature
- Reads the article aloud line by line.
- Highlights the current sentence as it's read.
- Start/Stop controls for reading sessions.

### 5. ❓ Comprehension Quiz System
- Auto-generates 3–4 comprehension questions.
- Based on **named entity recognition**.
- Awards XP upon completion.

### 6. 🏆 Gamification & Progress Tracking
- **XP System**: 
  - +10 XP for learning a new word
  - +5 XP for each quiz question
- **Level-Up System**: Based on XP
- **Glossary** of learned words (with date)
- Progress tracked using persistent JSON data.

### 7. 🖥️ User Interface
- Tabbed interface with:
  - 📰 **Reading Tab**
  - 📈 **Progress Tab**
- Scrollable text area with syntax highlighting.
- Right panel for word information & progress.

---

## 🛠 Required Dependencies

```bash
pip install nltk spacy pyttsx3 tkinter
python -m spacy download en_core_web_sm

