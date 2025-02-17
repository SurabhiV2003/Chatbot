# Chatbot Using Flask and BlenderBot
This project demonstrates a simple chatbot application using Flask, Hugging Face's BlenderbotSmallForConditionalGeneration model, and ngrok to expose the Flask application publicly. The chatbot can engage in conversations by maintaining context and generating responses based on previous user inputs.

## Features
1. Simple chatbot interface
2. Context management for maintaining conversation history
3. Deployed using Flask and accessible via ngrok
4. Uses Hugging Face's BlenderbotSmallForConditionalGeneration for text generation

## Technologies Used
1. Flask: Web framework for Python
2. Hugging Face Transformers: Library for pre-trained transformer models
3. Blenderbot: Conversational AI model from Facebook
4. Pyngrok: Python wrapper for ngrok to create public URLs
5. Google Colab: Cloud-based Jupyter notebook environment

## Setup and Deployment
### Step 1: Install Required Libraries
Ensure the following libraries are installed: Flask, transformers, torch, and pyngrok.

### Step 2: Define and Run Flask App
Create and run the Flask app in your Google Colab environment.

### Step 3: Start ngrok Tunnel
Start an ngrok tunnel to expose your Flask app to the public internet.

After completing these steps, you will see a public URL generated by ngrok. Open this URL in your web browser to access the Flask app and start chatting with the bot.
