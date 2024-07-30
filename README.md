# Multi Language Invoice Extractor

This project is a Streamlit-based web application that uses Google's Gemini Pro Vision AI to extract and analyze information from invoices in multiple languages. Users can upload an invoice image and ask questions about its content in natural language.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Features

- Upload invoice images in various formats (JPG, JPEG, PNG)
- Ask questions about the invoice content using natural language
- Receive comprehensive responses generated by Gemini Pro Vision AI
- Support for multiple languages (based on Gemini's capabilities)
- User-friendly interface built with Streamlit

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/multi-language-invoice-extractor.git
   cd multi-language-invoice-extractor
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your Google API key:
   - Create a `.env` file in the project root
   - Add your Google API key: `GOOGLE_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`)

3. Upload an invoice image using the file uploader

4. Enter your question about the invoice in the text input field

5. Click the "Tell me about the invoice" button to get the AI-generated response

## Configuration

The application uses the following environment variables:

- `GOOGLE_API_KEY`: Your Google API key for accessing Gemini Pro Vision

Make sure to keep your `.env` file secure and do not commit it to version control.

## How It Works

1. **Image Upload**: The user uploads an invoice image through the Streamlit interface.

2. **Question Input**: The user enters a question about the invoice content.

3. **AI Processing**: 
   - The application sends the image and question to Google's Gemini Pro Vision AI.
   - Gemini analyzes the image content and generates a response based on the question.

4. **Result Display**: The AI-generated response is displayed to the user in the Streamlit interface.

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` file for more information.
