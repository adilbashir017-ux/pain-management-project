# PainCare Assistant

A full-stack pain management platform designed to help patients track their pain, manage daily health information, and communicate relevant information with healthcare professionals.

🌐 **Live Demo:**  
https://pain-management-project-topaz.vercel.app/

## Features

### Patient
- Register and log in
- Submit daily pain reports
- Track pain history and trends
- View pain data through graphs
- Manage medication reminders
- View doctor notes
- Update personal profile information
- Use an AI-assisted chatbot for general, non-diagnostic guidance

### Doctor
- View assigned patients
- Review patient pain reports
- Monitor pain trends and high-pain alerts
- View patient clinical summaries
- Review medication status
- Add and manage doctor notes
- Update personal profile information

### Admin
- Manage doctors and patients
- Add or remove users
- Assign patients to doctors
- Update patient-doctor assignments

## Tech Stack

### Frontend
- React
- Vite
- JavaScript
- React Router
- React Hooks
- Tailwind CSS

### Backend
- Node.js
- Express.js
- REST API

### Database
- MongoDB

### AI Integration
- Google Gemini API

### Deployment
- Frontend: Vercel
- Backend: Render

## Project Structure

```text
pain-management-project/
├── paincare-assistant/   # React frontend
├── server/               # Node.js / Express backend
├── package.json
├── README.md
└── use-case-diagram.png
```

## System Use Case Diagram

The following diagram illustrates the main interactions between patients, doctors, administrators, and the Gemini AI service.

![PainCare Assistant Use Case Diagram](docs/use-case-diagram.png)

## Main Purpose

PainCare Assistant combines pain reporting, medication reminders, data visualization, doctor monitoring, administrative management, and AI-assisted interaction in a single full-stack web application.

The platform uses a React-based frontend, a Node.js and Express backend, MongoDB for persistent data storage, and the Google Gemini API for chatbot functionality.

## Project Context

PainCare Assistant was developed as a team project for the **Advanced Web Technologies** course at Braude College of Engineering.

## Live Application

👉 [Open PainCare Assistant](https://pain-management-project-topaz.vercel.app/)

## Author

**Adel Bashir**  
B.Sc. Software Engineering Student  
Braude College of Engineering

[LinkedIn](https://www.linkedin.com/in/adel-bashir/)
