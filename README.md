# CodeCraft AI

An AI-driven learning platform for medical coding that provides personalized learning experiences through adaptive content delivery and intelligent feedback.

## Project Overview

CodeCraft AI is a comprehensive learning platform that combines modern technology with medical coding education. The platform uses artificial intelligence to adapt to each user's learning pace and style, providing personalized recommendations and feedback.

### Key Features

- Personalized learning paths
- Interactive tutorials and lessons
- AI-powered feedback system
- Progress tracking and analytics
- Cross-platform support (iOS, Android, Web)

## Technology Stack

### Frontend
- Flutter (Cross-platform framework)
- Riverpod (State management)
- Material Design / Cupertino

### Backend
- Python (FastAPI/Flask)
- JWT Authentication
- RESTful APIs

### AI Model
- PyTorch
- Adaptive Learning Models
- Natural Language Processing

### Database
- MongoDB

## Project Structure

```
codecraft-ai/
├── frontend/               # Flutter application
│   ├── lib/
│   ├── test/
│   └── pubspec.yaml
├── backend/                # Python backend
│   ├── api/
│   ├── models/
│   ├── utils/
│   └── requirements.txt
├── ai_model/              # PyTorch AI models
│   ├── models/
│   ├── training/
│   └── utils/
├── docs/                  # Documentation
└── README.md
```

## Getting Started

### Prerequisites

- Flutter SDK
- Python 3.8+
- MongoDB
- PyTorch

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Oterochris/codecraft-ai.git
   cd codecraft-ai
   ```

2. Set up the frontend:
   ```bash
   cd frontend
   flutter pub get
   ```

3. Set up the backend:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   pip install -r requirements.txt
   ```

4. Set up the database:
   - Install MongoDB
   - Create a new database
   - Configure connection settings

## Development

### Running the Frontend

```bash
cd frontend
flutter run
```

### Running the Backend

```bash
cd backend
python main.py
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.