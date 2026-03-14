# CSM Dashboard - React AI Studio App

## Overview
A React + TypeScript + Vite frontend application that uses Google's Gemini AI API. It renders a Customer Success Manager (CSM) dashboard with components including a main dashboard, deliverable brief, and user timeline.

## Architecture
- **Framework**: React 19 + TypeScript
- **Build tool**: Vite 6
- **Styling**: Tailwind CSS v4 (via @tailwindcss/vite plugin)
- **AI**: Google Gemini AI (@google/genai)
- **Charts**: Recharts
- **Animation**: Motion (Framer Motion)
- **Icons**: Lucide React

## Project Structure
```
src/
  App.tsx              # Root component
  main.tsx             # Entry point
  index.css            # Global styles
  components/
    CSMDashboard.tsx   # Main dashboard component
    DeliverableBrief.tsx
    UserTimeline.tsx
index.html             # HTML template
vite.config.ts         # Vite configuration
package.json
tsconfig.json
```

## Environment Variables
- `GEMINI_API_KEY` - Required for Gemini AI API calls (set in Replit Secrets)

## Development
- Dev server runs on port 5000, host 0.0.0.0
- All hosts allowed for Replit proxy compatibility

## Deployment
- Static deployment: `npm run build` → `dist/` directory
