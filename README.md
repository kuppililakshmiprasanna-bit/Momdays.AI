# Momdays.ai

**Momdays.ai** is an AI-powered hybrid app designed to help women organize their day-to-day lives in sync with their menstrual cycle, mood, and energy levels. It blends personalized wellness insights, scheduling, and self-care recommendations —
 helping users plan better and live healthier.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Locally](#running-locally)
- [Usage](#usage)
- [Configuration](#configuration)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- 🌸 **Cycle-Aware Planner** — Personalized scheduling aligned with menstrual cycle phases.  
- 🤖 **AI Assistant (Gemini)** — Chat-based wellness guidance and journaling insights.  
- 📅 **Google Calendar Sync** — Integrates with your calendar for reminders and routines.  
- 🔐 **Firebase Authentication** — Secure login and data access control.  
- ☁️ **Cloud Firestore Database** — Real-time data storage and sync.  
- 📊 **Mood & Health Tracking** — Logs patterns for energy, emotion, and focus analytics.

---

## Tech Stack

- **Frontend:** Next.js (React) + Tailwind CSS  
- **Backend:** Firebase Cloud Functions  
- **Database:** Firebase Firestore  
- **AI/ML:** Google Gemini API (Generative AI)  
- **Auth:** Firebase Authentication  
- **Deployment:** Firebase Hosting  
- **Integration:** Google OAuth (Calendar Events API)

---

## Getting Started

### Prerequisites

Ensure you have installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) >= 18
- [Firebase CLI](https://firebase.google.com/docs/cli)
- A **Google Cloud Project** with **Calendar API** and **Gemini API** access
- `.env` file with your API keys (see [Configuration](#configuration))

### Installation

Clone the repository:

```bash
git clone https://github.com/kuppililakshmiprasanna-bit/Momdays.ai.git
cd Momdays.ai
