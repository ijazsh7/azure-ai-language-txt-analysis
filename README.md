zure AI Language – Text Analytics Lab

This project demonstrates how to use Azure AI Language (Text Analytics) with Python to analyze unstructured text. The lab performs language detection, sentiment analysis, key phrase extraction, and entity recognition on sample text files using the Azure SDK.

Project Structure
text-analysis/
├── reviews/              # Sample text files
├── labenv/               # Python virtual environment
├── text-analysis.py      # Main application script
├── requirements.txt      # Python dependencies
├── .env                  # Azure configuration (not committed)
└── README.md

Setup & Run
Prerequisites

Python 3.9+

Azure AI Language resource (endpoint & key)

Steps
# Create and activate virtual environment
python -m venv labenv
labenv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python text-analysis.py


Create a .env file:

AI_SERVICE_ENDPOINT=https://<your-resource>.cognitiveservices.azure.com/
AI_SERVICE_KEY=<your-key>

Sample Output
Language: English
Sentiment: Positive
Key Phrases: customer support, product
Entities: Microsoft, United States

Tools Used

Azure AI Language (Text Analytics)

Python

Azure SDK for Python (azure-ai-textanalytics)

python-dotenv