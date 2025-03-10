# AI Interview Bot

## Project Overview
The AI Interview Bot is an intelligent, voice-driven chatbot designed to assist users in preparing for job interviews by simulating real interview scenarios. It utilizes Speech-to-Text (STT) and Text-to-Speech (TTS) technologies to interact with users. The system is powered by NLP models to generate dynamic, adaptive interview questions based on user responses. Additionally, it generates structured reports after each session, which can be exported in formats like PDF, CSV, and JSON.

## Features
- **Voice Interaction**: Speech-to-Text and Text-to-Speech APIs for real-time voice commands and responses.
- **Dynamic Question Generation**: Adaptive interview questions tailored to different job roles and industries.
- **Real-Time Feedback**: Continuous interaction and counter-questioning during the interview process.
- **Report Generation**: Generate structured interview reports in JSON, PDF, or CSV format.
- **Cloud Deployment**: Deployed on cloud platforms like AWS, GCP, or Azure for scalability.

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask or Django)
- **Speech-to-Text & Text-to-Speech APIs**: Google Cloud, Microsoft Azure, Mozilla DeepSpeech, WebSpeech API
- **Natural Language Processing**: DialogFlow, ChatGPT fine-tuning
- **Cloud Services**: AWS, Google Cloud, Azure
- **Database**: Firebase or MongoDB for storing user data
- **PDF Report Generation**: Pandas, ReportLab, fpdf



## Installation & Setup
### Prerequisites
- Python 3.x
- Node.js (for frontend development)
- Git
- Cloud account (AWS/GCP/Azure)

### Step-by-Step Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/MairahNisar1234/ai-interview-bot.git
    cd ai-interview-bot
    ```

2. Install backend dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Install frontend dependencies:
    ```bash
    npm install
    ```

4. Set up environment variables for API keys (Speech-to-Text, NLP, etc.).

5. Run the backend server:
    ```bash
    python app.py
    ```

6. Run the frontend development server:
    ```bash
    npm start
    ```

### Testing the APIs
You can use Postman to test the various API endpoints. The following endpoints are available:
- `POST /api/voice-to-text`: Converts speech to text.
- `POST /api/generate-question`: Generates an interview question based on the user’s input.
- `POST /api/generate-report`: Creates a structured report after the interview.

## Contributing
1. Fork this repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Google Cloud Speech-to-Text](https://cloud.google.com/speech-to-text)
- [DialogFlow](https://dialogflow.cloud.google.com/)
- [ChatGPT](https://openai.com/)
- [ReportLab](https://www.reportlab.com/)

