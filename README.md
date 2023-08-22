# Interactive Assistant for Linux Terminal Commands

![Assistant GIF](https://media.giphy.com/media/5k5vZwRFZR5aZeniqb/giphy.gif)

This code implements an interactive assistant that simulates a Linux terminal. It uses the GPT-3 model provided by OpenAI to generate terminal commands and responses based on user inputs. The assistant can receive voice commands and text inputs, providing terminal commands as output.

...

[View GIF on GIPHY](https://giphy.com/gifs/content-jasper-ai-5k5vZwRFZR5aZeniqb)

This code implements an interactive assistant that simulates a Linux terminal. It uses the GPT-3 model provided by OpenAI to generate terminal commands and responses based on user inputs. The assistant can receive voice commands and text inputs, providing terminal commands as output.

## How the Code Works

The code uses the `langchain` library along with the GPT-3 model to create a conversational chain. It interacts with the user in the following manner:
1. The user provides input, either as text or voice command.
2. The input is processed, and the assistant generates a terminal command response.
3. The terminal command response is executed on the system.

The code includes the following functionalities:
- Generating terminal command responses based on user input.
- Converting speech to text for input.
- Executing terminal commands on the system.

## Usage

1. Make sure you have the required libraries installed:
   - langchain
   - pyttsx3
   - speech_recognition
   - [OpenAI Python](https://github.com/openai/openai-python)

2. Replace `"YOUR_GPT_KEY"` in the `OPENAI_API_KEY` variable with your actual OpenAI API key.

3. Run the script using a Python interpreter.

4. The assistant will prompt you to speak or provide text input. Once input is provided, it will generate a terminal command response and execute it.

## Advantages

- **Interactive Learning**: The assistant can be used to learn and practice Linux terminal commands interactively.
- **Voice Input**: The assistant supports voice input, making it convenient to interact even without typing.
- **Quick Reference**: It can serve as a quick reference for Linux commands and their corresponding outputs.

## Important Note

- This code requires an active internet connection to use the OpenAI API for generating responses.
