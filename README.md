# Intelligent ChatBot

A simple browser-based AI chatbot interface built with HTML, CSS, and JavaScript.

## Project Overview

This project implements a lightweight chat UI that lets users send messages and receive bot responses via the Google Gemini generative language API. It also supports image attachment previews and an emoji picker.

## Files

- `index.html` - main page structure and chatbot UI layout.
- `style.css` - styling for the chatbot popup, messages, input form, attachments, and animation.
- `script.js` - chat logic, API call handling, emoji picker, file upload preview, and message rendering.

## Features

- Chat popup interface with bot and user message bubbles
- Text input with emoji picker
- File attachment preview for image uploads
- Message submission via send button or Enter key
- Bot typing indicator while waiting for API response
- Simple responsive styling with modern dark theme

## Setup

1. Clone or download the repository.
2. Open the project folder in your code editor.
3. Open `index.html` in a web browser.

## Usage

1. Type a message in the text area.
2. Press `Enter` or click the send arrow button to submit.
3. Optionally attach an image by clicking the attach button.
4. The bot response is fetched from the Google Gemini API and displayed in the chat.

## Important Notes

- Use your own API Key 
- The bot response depends on the Google Generative Language API endpoint configured in `script.js`.
- The emoji picker loads from `https://cdn.jsdelivr.net/npm/emoji-mart@latest/dist/browser.js`.

## Customization

- Change the UI colors and layout in `style.css`.
- Update or replace the API endpoint and request format in `script.js`.
- Replace the bot graphics or header text in `index.html`.

## License

This project is open source and free to use for learning and demo purposes.
