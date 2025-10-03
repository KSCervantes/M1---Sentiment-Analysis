# M1 - Sentiment Analysis

A comprehensive sentiment analysis application built with Streamlit that analyzes customer reviews using multiple AI models including Google's Gemini AI, VADER sentiment analysis, and Hugging Face transformers.

## Features

- 🤖 **Multiple AI Models**: Uses Google Gemini AI, VADER, and Transformers for comprehensive sentiment analysis
- 📊 **Interactive Visualizations**: Beautiful charts and graphs using Plotly
- 🌐 **Web Interface**: User-friendly Streamlit web application
- 📈 **Real-time Analysis**: Instant sentiment scoring and classification
- 📄 **CSV Processing**: Analyze customer reviews from CSV files

## Prerequisites

- Python 3.7+
- Google Gemini API key (free from [Google AI Studio](https://makersuite.google.com/app/apikey))

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KSCervantes/M1---Sentiment-Analysis.git
   cd M1---Sentiment-Analysis
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**:
   Create a `.env` file in the project root and add your Gemini API key:
   ```
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

## Usage

1. **Start the application**:
   ```bash
   streamlit run app.py
   ```

2. **Access the web interface**:
   Open your browser and go to `http://localhost:8501`

3. **Analyze sentiment**:
   - The app will load the sample customer reviews dataset
   - View sentiment analysis results with interactive charts
   - Explore different sentiment analysis models and their outputs

## Project Structure

```
├── app.py                 # Main Streamlit application
├── customer_reviews.csv   # Sample dataset with customer reviews
├── requirements.txt       # Python dependencies
├── .env                  # Environment variables (not tracked in git)
├── .gitignore           # Git ignore file
└── README.md            # Project documentation
```

## Dependencies

- **streamlit**: Web application framework
- **pandas**: Data manipulation and analysis
- **plotly**: Interactive data visualizations
- **google-generativeai**: Google's Gemini AI integration
- **python-dotenv**: Environment variable management
- **vaderSentiment**: VADER sentiment analysis
- **transformers**: Hugging Face transformers for NLP
- **torch**: PyTorch for deep learning models
- **nltk**: Natural Language Toolkit

## API Key Setup

### Getting a Google Gemini API Key:

1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Create a new API key
4. Copy the key and add it to your `.env` file

### Environment Variables:

The application supports both local development and cloud deployment:

- **Local Development**: Uses `.env` file
- **Streamlit Cloud**: Uses Streamlit secrets

## Features in Detail

### Sentiment Analysis Models:

1. **Google Gemini AI**: Advanced language model for nuanced sentiment understanding
2. **VADER Sentiment**: Rule-based sentiment analysis optimized for social media text
3. **Transformers**: Pre-trained models from Hugging Face for deep learning-based analysis

### Data Visualization:

- Sentiment distribution charts
- Review score analysis
- Interactive plotly graphs
- Real-time sentiment scoring

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google AI for the Gemini API
- Streamlit for the web framework
- Plotly for interactive visualizations
- The open-source community for the various NLP libraries

## Support

If you encounter any issues or have questions, please open an issue in the GitHub repository.

---

**Note**: Remember to keep your API keys secure and never commit them to version control!