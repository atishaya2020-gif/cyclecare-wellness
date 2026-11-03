# CycleCare — Frontend Prototype

A responsive, interactive React + Vite frontend for **AI-Based Menstrual Cycle Prediction and Women's Health Assistant**.

## Included
- Marketing landing page and welcome/signup modal
- Dashboard overview with cycle day and estimated dates
- Period logging and adjustable cycle settings
- Interactive calendar with period and ovulation estimates
- Mood and symptom check-ins saved to browser LocalStorage
- Health insights based on locally entered check-ins
- Mock conversational wellness assistant (no external AI API)
- Light/dark theme toggle
- Responsive desktop and mobile layouts

## Run locally
Requires Node.js 18+.

```bash
npm install
npm run dev
```

Then open the local URL printed by Vite (usually http://localhost:5173).

To create a production build:

```bash
npm run build
npm run preview
```

## Notes
- Frontend-only: no authentication, backend, database, or real AI/ML model yet.
- Data is stored in browser LocalStorage on the current device.
- Cycle and ovulation dates are estimates for demonstration only, not medical predictions or advice.
- The assistant uses predefined responses and is not connected to a real AI service.
- Later, connect the frontend to Django REST Framework endpoints and a validated prediction model.
