# gemini-vision-qna-
#This project is a Gemini AI-powered Q&A application using Streamlit and Google's **gemini-1.5-flash** model. 
The application allows users to input questions and receive AI-generated responses, with support for image-based queries.

![screencapture-localhost-8501-2025-03-10-11_44_08](https://github.com/user-attachments/assets/4546bc77-93a9-4b4b-835e-445dd49d15df)


**Features**

Uses Google Gemini API for AI-generated responses.

Streamlit-based UI for user-friendly interaction.

Accepts text-based questions.

Supports image-based queries (upload an image and ask questions about it).

Live streaming responses from the model.

**Installation**

**1. Clone the repository**

https://github.com/Saurabhvarpe01/GeminiAI.git

**2. Create a virtual environment (optional but recommended)**
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows

**3. Install dependencies**
pip install -r requirements.txt

**4. Set up API Key**
Create a .env file and add your Google API Key:

GOOGLE_API_KEY=your_google_api_key_here

**Usage**

Run the Streamlit app:

streamlit run app.py

**Example Questions**

"Describe the objects present in this image."

"What futuristic elements can you identify in this cityscape?"

"What improvements can be made to this workspace setup?"

**Demo Video**




https://github.com/user-attachments/assets/dbc590d7-1a80-4a42-890d-2d2d0083a2ee


