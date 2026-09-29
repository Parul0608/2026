# Post Composer (React)

A simple responsive React app for composing social media posts for Twitter/X and LinkedIn.

## Features

- Switch between Twitter/X and LinkedIn.
- Twitter/X character limit: 280 characters.
- LinkedIn character limit: 3,000 characters.
- Live character count and remaining-character count.
- Error message when the selected platform's limit is exceeded.
- Submit button is disabled for empty posts or posts over the limit.
- Responsive layout for desktop and mobile screens.

## Requirements

- Node.js 18 or later
- npm

## Run locally

1. Extract the ZIP file.
2. Open a terminal inside the project folder.
3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL shown in the terminal (usually `http://localhost:5173`).

## Build for production

```bash
npm run build
```

## Upload to GitHub

1. Create a new repository on GitHub.
2. Extract this ZIP file on your computer.
3. Open a terminal in the extracted `post-composer-react` folder.
4. Run these commands, replacing the URL with your repository URL:

   ```bash
   git init
   git add .
   git commit -m "Add React Post Composer"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git push -u origin main
   ```

The app only demonstrates composing and validating a post; it does not connect to or publish through Twitter/X or LinkedIn APIs.
