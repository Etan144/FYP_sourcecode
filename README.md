# DG (Deepfake Guard) - FYP Source Code

A comprehensive full-stack application for detecting and managing deepfakes in communications, featuring:
- **Android App** - Deepfake Speech Detection during calls (Kotlin + Jetpack Compose)
- **Web Backend** - Firebase-based backend with Cloud Functions (Node.js + TypeScript)
- **ML Training** - Python-based AI model for deepfake detection

## Project Structure

### Frontend (Android)
- **Repository**: [FYP-25-S4-23-1](https://github.com/seeyu44/FYP-25-S4-23-1)
- **Branch**: master
- **Architecture**: BCE (Boundary-Control-Entity) MVVM pattern
- **Tech Stack**: Kotlin + Jetpack Compose, Firebase Auth, SQLite, on-device ML inference
- **Key Features**:
  - User authentication (Firebase Auth)
  - Real-time deepfake detection during calls
  - Call history tracking
  - Admin dashboard for user management
  - Background detection service

### Backend
- **Repository**: [DG_FirebaseBackend](https://github.com/Etan144/DG_FirebaseBackend)
- **Branch**: main
- **Tech Stack**: Firebase Cloud Functions, Firestore, Node.js + TypeScript
- **Frontend**: React + Vite web interface
- **Key Features**:
  - User authentication (phone verification, email)
  - Call management and tracking
  - Deepfake detection scoring
  - Admin dashboard and analytics
  - Reviews & ratings system
  - Subscription management

## Getting Started

### Frontend (Android)
```bash
cd frontend
# Open in Android Studio and build
# See folder/README.md for detailed setup
```

### Backend
```bash
cd backend
# Install dependencies
cd functions
npm install
npm run build

# Setup and run Firebase emulator or deploy
```

## Documentation

- See `frontend/README.md` for Android app setup and architecture details
- See `backend/README.md` for backend setup, Firebase configuration, and deployment instructions

