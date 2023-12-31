# RateMyResume

RateMyResume is a web application designed to provide AI-generated feedback on resumes. Users can upload their resumes, and optionally provide a job description, to receive tailored feedback and suggestions for improvement.
It is live! Hosted on the streamlit community cloud @ https://ratemyresume.streamlit.app/

## Features

- **AI-Powered Feedback**: Uses Google's Generative AI to analyze resumes and provide feedback.
- **PDF Support**: Users can upload their resumes in PDF format.
- **Job Description Analysis**: Users can provide a job description to get feedback tailored to a specific job role.
- **Personal Info Sanitization**: The application ensures that personal information like email addresses, phone numbers, and links are sanitized before processing.

## Installation

1. Clone the repository:
  git clone https://github.com/samarth6341/ratemyresume.git

2. Navigate to the repository directory:
   cd ratemyresume
3. Install the required Python libraries:
  pip install -r requirements.txt

## Usage

1. Run the Streamlit application:
2. Open the provided link in your web browser.
3. Upload your resume in PDF format.
4. (Optional) Provide a job description to get tailored feedback.
5. Click on "Process PDF" to receive feedback.

## Dependencies

- `streamlit`: For creating the web interface.
- `google-generativeai`: For generating feedback on the resume.
- `PyMuPDF`: For reading PDF files.

## Scope
Working on making the results more data driven.

## License
This project is open-source. Feel free to fork, modify, and use as you see fit.

