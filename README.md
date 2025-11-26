# Photon : AI-Powered Album Sorter 📸

An intelligent photo management system that uses facial recognition to automatically organize and sort your photos in shared albums.

<details>
<summary>Contents</summary>

* [Description](#description)
* [Tech Stack](#tech-stack)
* [Real-time Use Applications](#real-time-use-applications)
* [Features](#features)
* [Installation & Setup](#installation--setup)
* [Web Application Demo](#web-application-demo)
</details>

## Description

AI-Powered Album Sorter is a modern web application that revolutionizes how you organize and share photos. Using advanced facial recognition technology, it automatically identifies and categorizes photos based on the people in them. Users can create shared albums, upload photos, and easily find pictures of themselves or others through intelligent facial scanning.

## Tech Stack

### Frontend
- React.js
- Material-UI
- Axios
- React Router

### Backend
- FastAPI
- Python 3.8+
- JWT Authentication
- OAuth2

### AI/ML
- MTCNN (Multi-task Cascaded Convolutional Networks)
- FaceNet
- Cosine Similarity

### Database & Storage
- MongoDB
- Cloudinary

## Real-time Use Applications

- **Family Events**: Automatically sort photos from family gatherings by individual family members
- **Corporate Events**: Organize conference or team-building photos by participants
- **Wedding Photography**: Quick sorting of wedding photos based on guests
- **School Events**: Categorize yearbook photos or event photos by students
- **Travel Groups**: Share and sort group trip photos efficiently

## Features

### Core Features
- 🔐 Secure authentication using OAuth2 and JWT
- 👤 Advanced facial recognition and matching
- 📁 Create and manage shared albums
- ⚡ Real-time photo uploading and processing
- 🔍 Smart search functionality
- 👥 Multi-user album access
- 🖼️ Automatic photo categorization
- 📱 Responsive design for mobile and desktop

### AI Features
- Face detection using MTCNN
- Feature embedding extraction with FaceNet
- Intelligent photo grouping using cosine similarity
- Continuous learning from new uploads

## Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- Python 3.8+
- MongoDB
- Cloudinary account
- Git

### Clone Repository
```bash
git clone https://github.com/Anika-2048/Automatic-Photo-Sorter.git
cd Automatic-Photo-Sorter
```
### Backend Setup
```bash
# Navigate to backend directory
cd backend

# Create virtual environment
python -m venv album-sorter
source album-sorter/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the server
uvicorn main:app --reload
```
### Frontend Setup
```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Run the development server
npm start
```

