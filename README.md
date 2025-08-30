# 🧪 VLabs - Electronics & Communication Virtual Laboratory

A comprehensive Flask-based virtual laboratory platform for Electronics and Communication Engineering experiments, featuring digital signal processing simulations, interactive quizzes, and hands-on learning modules.

## 🌟 Features

### 🔐 Authentication System
- **User Registration & Login**: Secure Firebase authentication
- **Email Verification**: Automated email verification for new users
- **Session Management**: Persistent user sessions with logout functionality

### 🧪 Virtual Experiments
- **10 Interactive Experiments**: Complete lab simulations with real-time results
- **Digital Signal Processing**: ASK, PSK, and BFSK modulation techniques
- **Parameter Customization**: Adjustable signal parameters for comprehensive learning
- **Visual Simulations**: Interactive waveform generation and analysis

### 📝 Assessment System
- **10 Comprehensive Quizzes**: Topic-wise assessments with instant scoring
- **Real-time Feedback**: Immediate score calculation and result display
- **Progress Tracking**: Monitor learning progress across different modules

### 🔬 Supported Experiments
1. **Experiment 1-10**: Various electronics and communication concepts
2. **ASK Modulation** (Exp 2): Amplitude Shift Keying simulation
3. **BFSK Modulation** (Exp 3): Binary Frequency Shift Keying
4. **PSK Modulation** (Exp 4): Phase Shift Keying implementation
5. **Advanced Signal Processing** (Exp 7, 9): Complex signal analysis

## 🚀 Quick Start

### Prerequisites
- Python 3.7+
- Firebase account and project setup
- Required Python packages (see requirements.txt)

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/vlabs-extc.git
cd vlabs-extc

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install flask pyrebase sqlite3 collections

# Set up Firebase configuration
# Update the config dictionary in app.py with your Firebase credentials

# Run the application
python app.py
```

### Access the Application
- Open your browser and navigate to `http://localhost:5000`
- Register a new account or login with existing credentials
- Explore experiments and take quizzes

## 🏗️ Project Structure

```
vlabs-extc/
├── app.py                 # Main Flask application
├── ASK.py                 # Amplitude Shift Keying module
├── PSK.py                 # Phase Shift Keying module  
├── BFSK.py                # Binary FSK module
├── templates/
│   ├── index.html         # Landing page
│   ├── loginPage.html     # Authentication page
│   ├── extc.html          # Main experiments dashboard
│   ├── experiments.html   # Experiments listing
│   ├── exp1.html - exp10.html    # Individual experiments
│   ├── sim1.html - sim10.html    # Simulation interfaces
│   └── quiz1.html - quiz10.html  # Quiz templates
├── static/
│   ├── css/              # Stylesheets
│   ├── js/               # JavaScript files
│   └── images/           # Static images
└── requirements.txt       # Python dependencies
```

## 🔧 Configuration

### Firebase Setup
Update the Firebase configuration in `app.py`:

```python
config = {
    "apiKey": "your-api-key",
    "authDomain": "your-domain.firebaseapp.com",
    "projectId": "your-project-id",
    "storageBucket": "your-bucket.appspot.com",
    "messagingSenderId": "your-sender-id",
    "appId": "your-app-id",
    "measurementId": "your-measurement-id",
    "databaseURL": "your-database-url"
}
```

### Environment Variables
```bash
# Set Flask secret key
export FLASK_SECRET_KEY="your-secret-key"

# Set Flask environment
export FLASK_ENV="development"  # or "production"
```

## 📊 Experiment Details

### ASK Modulation (Experiment 2)
- **Parameters**: Carrier amplitude, frequency, pulse signal frequency
- **Output**: Real-time waveform generation and analysis
- **Learning Outcomes**: Understanding amplitude modulation principles

### BFSK Modulation (Experiment 3)
- **Parameters**: Sample rate, bit rate, frequencies, duration, amplitude
- **Features**: Dual-frequency signal generation
- **Applications**: Digital communication systems

### PSK Modulation (Experiment 4)
- **Parameters**: Carrier signal properties, pulse characteristics
- **Simulation**: Phase-shifted signal visualization
- **Use Cases**: Advanced digital modulation techniques

## 🎯 Quiz System

### Features
- **Automated Scoring**: Real-time score calculation (0-5 points per quiz)
- **Diverse Topics**: Covering all experiment areas
- **Instant Feedback**: Immediate results display
- **Multiple Choice**: User-friendly question format

### Sample Quiz Topics
- Basic electronics principles
- Digital signal processing
- Modulation techniques
- Communication systems
- Signal analysis

## 🔒 Security Features

- **Firebase Authentication**: Industry-standard security
- **Session Management**: Secure user session handling
- **Input Validation**: Form data sanitization
- **Error Handling**: Graceful error management

## 🚧 Development Roadmap

- [ ] **Mobile Responsiveness**: Optimize for mobile devices
- [ ] **Advanced Analytics**: Detailed progress tracking
- [ ] **More Experiments**: Expand to 20+ experiments
- [ ] **Real-time Collaboration**: Multi-user lab sessions
- [ ] **Export Functionality**: Download results and reports
- [ ] **API Integration**: RESTful API for external integrations

## 🛠️ Technologies Used

- **Backend**: Flask (Python)
- **Authentication**: Firebase/Pyrebase
- **Database**: SQLite3
- **Frontend**: HTML5, CSS3, JavaScript
- **Signal Processing**: Custom Python modules (ASK, PSK, BFSK)
- **Deployment**: Flask development server (configurable for production)

## 📈 Performance Optimizations

- **Lazy Loading**: Experiments load on-demand
- **Session Caching**: Reduced database queries
- **Optimized Routes**: Efficient URL routing
- **Static File Serving**: Fast asset delivery

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-experiment`)
3. Implement your changes
4. Add tests for new functionality
5. Commit changes (`git commit -am 'Add new experiment module'`)
6. Push to branch (`git push origin feature/new-experiment`)
7. Open a Pull Request

### Development Guidelines
- Follow PEP 8 Python style guide
- Add docstrings to all functions
- Include unit tests for new experiments
- Update documentation for new features

## 📚 Educational Impact

This platform serves as a comprehensive learning tool for:
- **Engineering Students**: Hands-on experience with digital systems
- **Educators**: Ready-to-use lab curriculum
- **Researchers**: Foundation for advanced signal processing studies
- **Industry Professionals**: Refresher training and skill development

## ⚠️ Known Issues & Limitations

- Some simulation modules require optimization for large datasets
- Mobile interface needs responsive design improvements
- Advanced experiments may require additional computational resources

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Electronics and Communication Engineering curriculum standards
- Digital signal processing research community
- Flask and Firebase development communities

***

## GitHub Repository Description

```
Virtual Laboratory platform for Electronics & Communication Engineering with Flask, Firebase authentication, digital signal processing experiments (ASK/PSK/BFSK), interactive quizzes, and real-time simulations for hands-on learning.
```

## Recommended Topics/Tags

### Core Technologies
- `flask`
- `python`
- `firebase`
- `pyrebase`
- `sqlite`
- `web-application`

### Educational Focus
- `virtual-laboratory`
- `e-learning`
- `education-technology`
- `engineering-education`
- `interactive-learning`
- `online-experiments`

### Electronics & Communication
- `digital-signal-processing`
- `ask-modulation`
- `psk-modulation`
- `bfsk-modulation`
- `electronics-engineering`
- `communication-systems`
- `signal-processing`

### Features
- `quiz-system`
- `user-authentication`
- `simulations`
- `real-time-visualization`
- `laboratory-management`
- `academic-platform`

### Technical Implementation
- `web-based-simulation`
- `educational-software`
- `laboratory-automation`
- `student-assessment`
- `experiment-simulation`

## Repository Settings

**Primary Language**: Python  
**License**: MIT License (recommended for educational projects)  
**Include in search**: ✅ Enabled  
**Discussions**: ✅ Enable for educational discussions  
**Issues**: ✅ Enable for bug reports and feature requests  
**Wiki**: ✅ Enable for detailed documentation
