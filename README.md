# CardAssistant

AI-powered banking assistant mobile application built with React Native (Expo) and Supabase.

## Project Structure

```
CardAssistant/
├── backend/           # Supabase database and functions
│   └── supabase/
│       └── migrations/
│
├── frontend/          # React Native Expo app
│   ├── src/
│   ├── App.tsx
│   └── package.json
│
└── README.md          # This file
```

## Getting Started

### 1. Backend Setup

See [backend/README.md](./backend/README.md) for database setup instructions.

### 2. Frontend Setup

```bash
cd frontend
npm install
npx expo start
```

See [frontend/README.md](./frontend/README.md) for more details.

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React Native, Expo, TypeScript |
| Backend | Supabase (PostgreSQL, Auth, RLS) |
| Styling | React Native StyleSheet |
| State | React Context API |
