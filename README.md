# Beyond-QWERTY: Form-Filling Project

## Quick Links
- 🌐 [Live Website](https://voice-bank-form.onrender.com/)
- 📱 [Download Android APK](https://github.com/ARYANJATHAR/QWERTY_FORM_FILLING_PROJECT/blob/main/BankForm.apk)
- 🎥 [Watch Demo Video](https://drive.google.com/file/d/1SUTJHkhfNT-ucLxOVnBwaBixPPvD-GKr/view?usp=sharing)

## ⚠️ Important Note
The website is hosted on Render's free tier, which means the server goes to sleep when inactive. On your first visit, it may take a few seconds to wake up (cold start). If you encounter a 502 (Bad Gateway error), please wait a few minutes and try again.

## Project Description
Beyond-QWERTY is a pioneering voice-enabled, cross-platform solution that revolutionizes bank account application form completion. The application offers dual input methods - voice and traditional text - making it accessible to a diverse user base. It seamlessly captures user data, performs real-time validation, and generates PDF applications that are automatically emailed to users. The project is available both as a web application and an Android application (APK), built from a unified codebase.

## Web Application Features

### 🔐 Secure User Authentication
- User sign-up and sign-in with email, password, and username
- Password hashing using bcrypt for enhanced security
- Robust session management
- Forgot Password functionality with time-limited reset tokens

### 📝 Interactive Bank Account Application Form
- Comprehensive form sections:
  - Personal information
  - Contact details
  - Employment status
  - Income details
  - Account preferences
  - Nominee information
- Voice input support for all text fields via Speech Recognition API
- Real-time error detection and display
- Dual validation: client-side and server-side

### 📄 PDF Generation and Email Notifications
- Automated PDF generation of completed applications using ReportLab
- Instant email delivery of application PDFs
- Automated password reset and confirmation emails

### 💾 Data Management
- Secure data storage using Supabase (cloud-based Postgres database)
- Protected API endpoints for database interactions

### 🎨 User Interface
- Modern, responsive design
- Light/dark theme toggle
- Intuitive layout with informative notifications
- Loading indicators for better user experience

## Android Application Features

### 📱 Mobile-First Experience
- Direct installation on Android devices
- Complete feature parity with web version
- Native app-like experience
- Smooth performance without browser dependency

## Technology Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask Framework

### Database
- Supabase (Postgres)

### Mobile Packaging
- PWA Builder for APK generation

## Project Structure
```
FORM/
├── .venv/
├── .vscode/
├── flask_session/
├── static/
│   ├── auth_script.js
│   ├── bank_script.js
│   └── bank_style.css
├── templates/
│   ├── auth_form.html
│   └── bank_form.html
├── .env
├── .env.example
├── app.log
├── app.py
├── README.md
└── requirements.txt
```

## Local Development Setup

### Prerequisites
- Python 3.6+
- pip
- Git
- Modern web browser with microphone support

### Installation Steps
1. Clone the repository:
```bash
git clone https://github.com/Nithin-Chakravarthi/Beyond-QWERTY__Form-Filling-Vernacular-Voyage-with-Voice-Versatility-.git
cd Beyond-QWERTY__Form-Filling-Vernacular-Voyage-with-Voice-Versatility-
```

2. Set up virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Unix/macOS
.venv\Scripts\activate     # On Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Configure environment variables:
- Create a `.env` file with:
```env
SECRET_KEY=your_secret_key
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
```

5. Run the application:
```bash
python app.py
```

## Contributing
We welcome contributions! Please feel free to submit pull requests.

## Conclusion
Beyond-QWERTY represents a significant step forward in making banking services more accessible through voice technology and cross-platform availability. The project demonstrates how modern web technologies can be leveraged to create user-friendly, secure, and efficient financial applications.
