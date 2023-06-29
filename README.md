# OCR-QA Bot

This is a Telegram bot that performs Optical Character Recognition (OCR) on images containing text and provides answers to questions related to the extracted text. It utilizes the OCR.space API for text extraction and the OpenAI GPT-3.5 Turbo model for answering questions.

## Prerequisites

Before running this bot, make sure you have the following:

- OCR.space API key: Obtain an API key from [OCR.space](https://ocr.space/ocrapi) to perform OCR on images. Replace `API_KEY` in the code with your actual API key.

- Telegram Bot token: Create a bot on Telegram and obtain a bot token by following the instructions in the [Telegram Bot API documentation](https://core.telegram.org/bots#botfather). Replace `TOKEN` in the code with your actual bot token.

- Python environment: Make sure you have Python installed on your system. This code is written in Python 3.

## Setup

1. Clone the repository or download the source code files to your local machine.

2. Install the required dependencies. You can use pip to install the dependencies listed in the `requirements.txt` file:

   ```
   pip install -r requirements.txt
   ```

3. Open the `README.md` file and replace `API_KEY` and `TOKEN` placeholders with your actual OCR.space API key and Telegram bot token, respectively.

## Usage

1. Run the bot script by executing the following command in your terminal:

   ```
   python ocr_qa_bot.py
   ```

2. Start a conversation with your Telegram bot. Search for the bot username on Telegram and send a message to start the interaction.

3. Send an image containing the text you want to extract and ask a question related to the text. The bot will perform OCR on the image, extract the text, and generate an answer to your question using the OpenAI GPT-3.5 Turbo model.

4. The bot will reply with the extracted text and the answer to your question.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code according to your needs.
