# ATS-Builder-LLM-Project

## Overview

ATS Builder is a powerful tool designed to enhance your resume and optimize it for Applicant Tracking Systems (ATS). It analyzes your resume, scores it against job descriptions, and provides a detailed profile summary along with suggestions for improvements.

## Features

- Resume scoring against job descriptions
- Profile summary generation
- Resume improvement recommendations

## Tech Stack

- **Streamlit:** Used for the user-friendly web application interface.
- **Google Generative AI:** Leveraged for advanced resume analysis.
- **PyPDF2:** Employed for PDF file handling.

## Getting Started

### Prerequisites

Make sure you have Python and the required libraries installed:

```bash
pip install streamlit google.generativeai PyPDF2 python-dotenv
```

### Installation

 Run the Streamlit app:

```bash
streamlit run app.py
```

## Usage

1. Upload your resume.
2. Get insights into how well it matches job descriptions.
3. Receive a detailed profile summary.
4. Follow suggested improvements to enhance your resume.

## Note
To enhance security and facilitate customization, consider adding a .env file to the project. This file will be the designated place for storing sensitive information, such as your Google API key

## Contributing

Feel free to contribute to the development of ATS Builder. Fork the repository, make your changes, and submit a pull request.

