# SERS — Smart E-Learning Recommendation System

SERS is a React/Vite learning-planner application that uses Gemini to generate study roadmaps and quizzes, with Firebase for authentication and cloud data.

## Features in the application

- Generate a learning roadmap from a learner's goal and current skill level.
- Create topic-focused quizzes from the roadmap.
- Track daily activity in a 30-day heatmap.
- Use a Pomodoro timer to support focused study sessions.
- Keep scratchpad notes associated with a learner's workspace.
- Export learning plans to PDF and calendar formats.

## Technology stack

- **Frontend:** React, Vite, CSS
- **AI:** Google Gemini API
- **Authentication and data:** Firebase Authentication and Cloud Firestore
- **Export:** Browser-side PDF and calendar generation

## Run locally

### Requirements

- Node.js and npm
- A Firebase project with Authentication and Firestore configured
- A Gemini API key

### Setup

1. Clone this repository and install dependencies:
   ```bash
   npm install
   ```
2. Create a `.env.local` file in the project root using `.env.example` as a guide.
3. Fill in the Firebase and Gemini values for your own projects. Never commit real API keys or private credentials.
4. Start the development server:
   ```bash
   npm run dev
   ```

## Configuration notes

The environment template documents the variables used by Firebase and Gemini. Authentication, database rules, and API usage limits must be configured in the corresponding provider dashboards before use.

## Attribution and repository scope

This repository is an authorised learning and portfolio adaptation of [Smart E-Learning Recommendation System (SERS) by Naresh Chary](https://github.com/NareshChary0430/Smart-Learning-Recommendation-System). The upstream project remains the source of the core application implementation. In this copy, repository-specific work is focused on environment configuration, local setup documentation, and portfolio packaging. The existing core source files should not be represented as independently written from scratch.

For an accurate view of the original implementation, see the upstream repository linked above.
