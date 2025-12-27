# Einstein AI Chat 🏛️

A conversational AI application that lets you chat with a digital persona of Albert Einstein. Powered by Google Gemini-1.5-Flash and LangChain.

## Features
- **Authentic Persona**: Responds as Albert Einstein with personal anecdotes and scientific reasoning.
- **Memory**: Remembers previous parts of the conversation.
- **Gradio UI**: User-friendly web interface with custom avatars.

## Prerequisites
- Python 3.9 or higher
- A Google Gemini API Key

## Installation

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/einstein_ai_chat.git](https://github.com/your-username/einstein_ai_chat.git)
cd einstein_ai_chat
```

### 2. Set Up a Virtual Environment (Recommended)
```
# Windows
python -m venv .venv
.venv\Scripts\activate

# macOS/Linux
python3 -m venv .venv
source .venv/bin/activate

```

### 3. Install Requirements
``` 
pip install -r requirements.txt
```
##### Note: If you don't have a requirements.txt yet, run 
 ```    
 pip install gradio langchain-google-genai python-dotenv langchain 
```

## Configuration:


1. Get your API Key from [Google AI Studio](aistudio.google.com).

2. Create a file named ```.env``` in the root directory.

3. Add your key to the file:
```
# Code snippet:

GEMINI_API_KEY=your_actual_key_here 
```
## Running the App

#### Execute the main script:
```
python main.py
```
Once running, open the local URL (usually http://127.0.0.1:7860) in your browser.
If ``page.launch(share=)`` is set to ``True`` then you will also get a public URL valid for a week.

### Usage

- Type your questions in the textbox to chat with Einstein.

- Use the Clear Chat button to reset the history.

- Ensure your avatar images (einstein.png and asuka.jpg) are in the project folder for the best experience. 
   * You can change ``asuka.jpg`` to something else, or to ``None``.