# Mistral-7B PDF Question Answering Application

This application uses the Mistral-7B model to generate Questions and Answers from PDF documents. Follow these steps to set up and run the application:
![Screenshot from 2024-08-09 17-20-59](https://github.com/user-attachments/assets/4df8a90b-1c00-4091-bc9b-596797d642fe)


## Setup Instructions

### 1. Clone the Repository

First, clone the repository to your local machine:

```sh
git clone https://github.com/Rjaat/Pdf-QnA-Mistral-7b.git
cd Pdf-QnA-Mistral-7b
```
### 2. Create a Virtual Environment

Create a virtual environment to isolate your project’s dependencies:

```sh
python3 -m venv venv
```
Activate the virtual environment:
```
source venv/bin/activate
```
### 3. Install Dependencies

Install the required dependencies from requirements.txt:
```
pip3 install -r requirements.txt
```
Additionally, ensure you have any other necessary libraries installed. If not included in requirements.txt, you may need to install them manually

### 4. Configure Hugging Face Token

Replace the Hugging Face token in app.py with your own token. Open app.py and find the section where the token is used. Replace it with your token:
```
# Example placeholder
login(token="PLACE_YOUR_TOKEN_HERE")     line No. 27 in app.py

```
### 5. Run the Application

Start the application by running app.py:
```
python3 app.py
```
### 6. Access the Application

Open your web browser and navigate to:
```
http://0.0.0.0:8000/
```
You should see the application’s user interface, where you can upload PDF files and ask questions.

### Troubleshooting
  -  Dependency Issues: Ensure all dependencies listed in requirements.txt are installed. If you encounter errors, try reinstalling them or checking compatibility.
  -  Token Errors: Make sure the Hugging Face token is valid and correctly placed in app.py.
  -  Port Issues: If 8000 is already in use, you might need to specify a different port in app.py.
