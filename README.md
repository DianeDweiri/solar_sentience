Solar Sentience
Solar Sentience is an interactive AI chatbot project that brings the solar system to life. Users can pick a celestial body—like the Sun, Earth, Mars, or even a Black Hole—and ask it questions. Each celestial entity responds with a unique personality, speaking in character with facts, humor, and emotion, powered by the Falcon RW-1B language model.

Features
Multiple Celestial Voices: Choose from planets, the Sun, Moon, and even a Black Hole, each with distinct personalities and speaking styles.

Dynamic Text Generation: Responses generated on the fly using the Falcon RW-1B model via Hugging Face Transformers.

Audio Output: Text-to-speech conversion using Google Text-to-Speech (gTTS) lets you hear the celestial responses.

Visual Enhancement: Accompanying animated GIFs provide a visual representation of each celestial body.

Beautiful UI: Custom-themed Gradio interface with animated starry background for an immersive space experience.

How It Works
Select a Celestial Body: Pick a planet or celestial object from the dropdown menu.

Ask a Question: Type your cosmic question in the input box.

Get a Response: The AI replies in character, combining known facts with engaging dialogue.

See and Hear: View a GIF of the celestial body and listen to the spoken reply.

Installation & Setup
This project runs smoothly in Google Colab, but you can run it locally with Python 3.8+.

Requirements
Python 3.8 or newer

transformers

gradio

gTTS

torch

Google Drive access (optional, if using for storing assets)

Install dependencies
bash
Copy
Edit
pip install gradio transformers gtts torch
Run the app
Simply run your Python script containing the Gradio app. If you're using Google Colab, mount your Google Drive for GIF storage.

Usage
Once running, open the provided Gradio link in your browser:

Choose a celestial body.

Enter your question.

Click "Transmit Question" and enjoy the interactive response.

Project Structure
reply_with_gif(planet, question): Main backend function that creates prompts, calls the AI model, generates speech, and provides GIFs.

planet_prompts & planet_data: Dictionaries storing personality prompts and factual data for each celestial body.

Gradio Blocks interface with custom CSS and JavaScript for visual effects.

Credits
Falcon RW-1B model by tiiuae

Gradio for UI framework

Google Text-to-Speech for audio synthesis

Planet GIFs (You should credit your source or create your own)

Future Improvements
Add more celestial bodies (e.g., dwarf planets, comets)

Include multilingual support

Enhance AI personality depth and emotional range

Enable conversation history and context awareness

## Author
Diane Waddah LutfAllah Dweiri  
Data Science Student | AI Enthusiast  
Amman, Jordan

## Contact
Email: Daiandnh8@gmail.com  
GitHub: [DianeDweiri](https://github.com/DianeDweiri)

