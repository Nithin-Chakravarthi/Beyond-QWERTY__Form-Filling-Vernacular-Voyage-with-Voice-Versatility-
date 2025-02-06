<<<<<<< HEAD
# **Beyond QWERTY: Form Filling's with Voice Versatility**

## **Overview**
The "Beyond QWERTY" project reimagines the traditional form-filling process by introducing a voice-driven, multilingual solution powered by **Azure OpenAI** and **GPT**. Designed to assist **Frontline Workers (FLWs)** in diverse fields, the system simplifies workflows, eliminates language barriers, and boosts productivity. Whether it's opening a bank account, creating a digital identity, or applying for jobs, this solution ensures an accessible and user-friendly experience.

---

## **Features**
- **Voice-Driven Form Filling**: Fill forms using natural language voice input.
- **Multilingual Support**: Overcome language barriers with real-time translation capabilities.
- **Workflow Automation**: Save time with auto-filled forms and seamless submissions.
- **Versatile Applications**: Adaptable for various use cases such as banking, job applications, and e-governance.
- **Secure and Scalable**: Ensures data privacy while supporting multiple users simultaneously.

---



![image](https://github.com/user-attachments/assets/4a211b1a-5f1a-4c91-9923-87765ead30ec)
=======
#Project Structure
FORM/
├── .venv/                     
├── .vscode/
├── flask_session/         -get created through library 
├── static/                -add like these 
│ ├── auth_script.js
│ ├── bank_script.js
│ └── bank_style.css
├── templates/             -add like these 
│ ├── auth_form.html
│ └── bank_form.html
├── .env
├── .env.example
├── app.log 
├── app.py                 -add like these 
├── README.md
└── requirements.txt

# Voice-Enabled Bank Form Application
[Click here to see the demo video](<https://drive.google.com/file/d/1SUTJHkhfNT-ucLxOVnBwaBixPPvD-GKr/view?usp=sharing>)
This is a web application for a bank form that uses voice input and provides user authentication.

## Local Setup Guide

Follow these instructions to run the application locally on your development machine.

### Prerequisites
-   **Python 3.6+:** Ensure Python is installed.
-   **pip:** Python package installer should also be installed.
-   **Git:** Version control system should be installed.
    * Install Git [here](https://git-scm.com/downloads)

### Step-by-step Installation
1.  **Clone the Repository:**

    ```bash
    git clone <YOUR_GITHUB_REPOSITORY_URL>
    cd <YOUR_PROJECT_DIRECTORY_NAME>
    ```

    *Replace `<YOUR_GITHUB_REPOSITORY_URL>` with the URL of your repository.*
    *Replace `<YOUR_PROJECT_DIRECTORY_NAME>` with the name of your project's directory.*

2.  **Set Up a Virtual Environment (Recommended):**

    ```bash
    python3 -m venv venv
    python -m venv venv(add any name)
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate # On Windows
    ```


3.  **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    pip install python-dotenv
    pip install bcrypt
    pip install requests
    pip  install flask-session
    pip install flask
    
    ```

4.  **Create a `.env` File:**

    *   Create a `.env` file in your project's root directory.

    *   Add the following variables to the `.env` file:

        ```env
        SECRET_KEY=<YOUR_SECRET_KEY>
        SUPABASE_URL=<YOUR_SUPABASE_URL>
        SUPABASE_KEY=<YOUR_SUPABASE_KEY>
        ```

        *   Replace `<YOUR_SECRET_KEY>` with a long, random string.
        *   Replace `<YOUR_SUPABASE_URL>` with your Supabase project URL.
        *   Replace `<YOUR_SUPABASE_KEY>` with your Supabase API key.

5.  **Run the Application:**

    ```bash
    python app.py
    ```
    The application will start on http://127.0.0.1:5000/

6.  **Open in your browser:**
     *   Open a web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to access the application.

7.  **Sign up with a valid email address (gmail.com, yahoo.com, outlook.com, hotmail.com, aol.com, or icloud.com)**
    *  Log in with the same credentials you created.
    *  Then fill in the form to submit to the database.
    
 ### Notes

-   Ensure the .env file is added to your .gitignore file to prevent pushing sensitive data.

### Dependencies
The dependencies for this project are listed in the `requirements.txt` file.

### Supabase Setup
This application uses Supabase as the backend for storing the user and bank form data. Please make sure you have properly setup your Supabase project and database tables according to the column names in `transform_payload` function.
>>>>>>> eac4b07 (project updated)




<<<<<<< HEAD
## **Technologies Used**
### **Frontend**
- HTML/CSS/JavaScript (if applicable for web-based interface)

### **Backend**
- **Python**: Flask or FastAPI
- **Node.js**: Express.js (alternative option)

### **Cloud Services**
- **Azure Cognitive Services**: Speech-to-Text, Translator API
- **Azure OpenAI**: GPT for language understanding
- **Azure App Services**: Deployment and hosting

### **APIs and Libraries**
- **Speech SDK**: Real-time voice recognition
- **Translator API**: Multilingual translation
- **PyTorch**: NLP model integration (optional)
- **REST/GraphQL**: API communication

### **Testing and Deployment**
- **Testing**: PyTest, Selenium
- **Deployment**: Azure Kubernetes Service (AKS), Azure Monitor

---

## **Modules**
1. **Voice Input and Language Processing**
   - Converts speech to text and maps it to form fields.
   - Supports real-time multilingual input and translation.

2. **Workflow Automation and Optimization**
   - Automates repetitive form-filling tasks.
   - Provides templates for various workflows.

3. **Integration with Existing Services**
   - Connects seamlessly with external systems like banking software or government platforms.

4. **Testing and Deployment**
   - Ensures the system is reliable, scalable, and user-friendly.

---

## **Setup Instructions**
### **Prerequisites**
- Python (3.8 or higher)

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/Nithin-Chakravarthi/Beyond-QWERTY__Form-Filling-Vernacular-Voyage-with-Voice-Versatility.git
   cd Beyond-QWERTY__Form-Filling-Vernacular-Voyage-with-Voice-Versatility
=======








>>>>>>> eac4b07 (project updated)
