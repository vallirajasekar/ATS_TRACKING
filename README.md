
# ATS Tracking

Access the application here: [ATS System](https://ats-tracking.onrender.com)

This project aims to streamline the hiring process by utilizing the Gemini model for efficient resume parsing and tracking. The ATS System reduces the need for traditional methods and offers enhanced accuracy and performance.

## Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/vallirajasekar/Multi-Language-Invoice-Extractor.git
cd ATS_SYSTEM
```

### Step 2: Create the Conda Environment
Create a new Conda environment with Python 3.10.
```bash
conda create -p venv python==3.10 -y
```

### Step 3: Activate the Environment
Activate the Conda environment.
```bash
conda activate "/Users/vallirajasekar/Desktop/gemini/ATS_SYSTEM/venv"
```

### Step 4: Install Dependencies
Install the required dependencies.
```bash
pip install -r requirements.txt
```

## Usage

### Set Up API Key
Make sure to set up your Google Generative AI API key. You can store it in a `.env` file in the root directory of your project:
```bash
GOOGLE_API_KEY=your_google_api_key
```

### Run the Streamlit Application
Start the Streamlit application by running:
```bash
streamlit run app.py
```

### Upload a Resume
1. Open the Streamlit app in your web browser.
2. Input your prompt in the text box.
3. Upload a PDF file of the resume.
4. Click on the "Submit & Process" button to get the extracted information.

## Description
The ATS System project is designed to simplify the extraction of information from resumes. Traditional methods like manual review require extensive time and are limited by human error. By leveraging the power of the Gemini model, this project aims to directly understand and extract information from resume documents.

### Key Features:
- **Multi-Language Support**: Capable of understanding resumes in different languages.
- **AI-Powered**: Utilizes Google Generative AI to process the content, reducing the need for manual review.
- **Easy to Use**: Simple web interface to upload documents and get results.

### How It Works:
1. **Input Prompt**: The user provides a prompt describing the task (e.g., "Extract resume details").
2. **Document Upload**: The user uploads a PDF of the resume.
3. **AI Processing**: The document and prompt are sent to the Gemini model, which processes the document and returns the extracted content.

## Acknowledgements
This project uses the following technologies:
- **Streamlit**: An open-source app framework for Machine Learning and Data Science.
- **Google Generative AI**: API for advanced AI models.

## Notes
- Ensure you have the necessary API key from Google Cloud for accessing the Generative AI services.
- This project is intended for educational and experimental purposes.

## Project Structure
```
ATS_SYSTEM/
│
├── app.py                # Main application script
├── main1.py              # Alternative main script
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
├── venv/                 # Conda virtual environment directory
├── data/                 # Directory for input data (e.g., PDFs)
├── models/               # Directory for storing models
├── outputs/              # Directory for outputs
└── .git/                 # Git version control directory
```

## Version Control with Git
This project uses Git for version control. Below are some basic commands to get you started:

### Initialize a new Git repository:
```bash
git init
```

### Add files to the staging area:
```bash
git add .
```

### Commit changes:
```bash
git commit -m "Initial commit"
```

### Add a remote repository:
```bash
git remote add origin <remote_repository_URL>
```

### Push changes to the remote repository:
```bash
git push -u origin master
```

!!! Thank You !!! Visit Us Again :)

## About
Utilizes Google Generative AI for efficient, accurate extraction of resume details from documents across multiple languages, enhancing automation and workflow for global hiring processes.
```

