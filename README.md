# Schuuul - Autonomous Learning Platform for Educators and Students

## Team Members

- Beda Diggelmann
- Maria Näf
- Nathalie Kern
- Pascal Ammeter

## Overview

Addressing the shortage of skilled educators in Switzerland, this project proposes an autonomous platform to aid teachers and students. By integrating generative AI, it aims to streamline lesson planning and enhance educational engagement.

## Content of this repository

- Technical implementation of the prototype.

## Getting Started

Follow these steps to run the application locally:

### Prerequisites

- Python
- Git

### Setup

Here's how you can run the application locally:

```bash
# Clone the repository
git clone <repository-url>

# Navigate to the project directory
cd kete-autonomous-learning-platfrom-schuuul

# Create a Python virtual environment in the 'venv' directory
python -m venv venv

# Activate the virtual environment (use the correct command for your operating system)
source venv/Scripts/activate # For Windows in Git Bash
# or
source venv/bin/activate # For Unix or Linux systems

# Install the project dependencies from 'requirements.txt'
pip install -r requirements.txt

# Create a '.env' file in the 'kete' directory with the following content
echo "OPENAI_API_KEY=XXX" >> .env

# Run the local development server or script (specify the script if it's not 'app.py')
streamlit run project/app.py
```
