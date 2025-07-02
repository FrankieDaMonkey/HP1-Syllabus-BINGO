# Health Promotion Bingo App

An interactive Bingo web app to help students engage with a public health syllabus, with AI-enhanced questions.

## 🛠 Setup

1. Clone this repo or unzip the folder.
2. Run `npm install` to install dependencies.
3. Set up a Firebase project and add `.env` file with your Firebase credentials (see `.env.sample`).
4. Run `npm start` to test locally.

## 🚀 Deploy

### Option A: Deploy to Vercel

1. Go to https://vercel.com
2. Import this project from GitHub or upload manually
3. Vercel will auto-detect React and deploy it

### Option B: Deploy to Firebase Hosting

1. Install Firebase CLI: `npm install -g firebase-tools`
2. Run `firebase login`
3. Run `firebase init` and select Hosting
4. Set public directory to `build`
5. Run `npm run build`
6. Run `firebase deploy`

Enjoy your Bingo!