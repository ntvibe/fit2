# FitBro

A progressive web app (PWA) for strength training - inspired by TechnoGym.

## 🚀 Quick Start

**Live Demo:** https://ntvibe.github.io/fit2/app/

## Features

### Workout Planning
- **Create workout plans** with custom names (PUSH, LEG DAY, etc.)
- **150+ exercises** across all muscle groups
- **Exercise autocomplete** - suggestions appear as you type
- **Filter by muscle**: Chest, Back, Legs, Shoulders, Arms, Core
- **Filter by equipment**: Barbell, Dumbbell, Cable, Machine, Bodyweight

### Exercise Library
- **Chest**: Bench Press, Incline Press, Fly, Push-ups, Dips (20+ exercises)
- **Back**: Deadlift, Rows, Pull-ups, Lat Pulldown, Shrugs (25+ exercises)
- **Legs**: Squat, Leg Press, Lunges, Hip Thrust, Curls (30+ exercises)
- **Shoulders**: Overhead Press, Lateral Raises, Front Raises (15+ exercises)
- **Arms**: Bicep Curls, Tricep Extensions, Skull Crushers (20+ exercises)
- **Core**: Planks, Crunches, Leg Raises, Cable Crunches (15+ exercises)

### Workout Execution
- **Edit workout plans** - DONE button saves changes
- **Log sets** with weight and reps
- **Track progress** during workout
- **Complete workouts** and save to history

### Progress Tracking
- Total workouts count
- Total exercises tracked
- **Streak counter** - consecutive days of training

### Design
- **Dark mode** (black background)
- **Yellow accent** for primary actions
- **Bottom navigation**
- **Bottom sheet modals**
- **Muscle badges** showing targeted areas
- **PWA** - Install on Android for full-screen experience

## Install on Android

1. Open https://ntvibe.github.io/fit2/app/ in Chrome
2. Tap **Menu** (⋮) → **Add to Home Screen**
3. The app will install and work offline

## Tech Stack

- Vanilla HTML/CSS/JavaScript
- localStorage for data persistence
- PWA (installable)
- Service Worker for offline support
- No build step required

## Development

```bash
# Open in browser
open app/index.html

# Or serve locally
npx serve app
```

## Deployment to GitHub Pages

1. Repository Settings → Pages
2. Source: Deploy from `main` branch
3. Folder: `/app`

## License

MIT
