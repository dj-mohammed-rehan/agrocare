# AgroCare

AI-powered crop diagnosis and treatment recommendations, built by Team Tech Titans.

AgroCare turns a phone or laptop camera into a crop doctor. Capture a photo of an affected plant and the app analyzes it with Google's Gemini model to identify likely diseases, pests or deficiencies, then suggests treatment steps.

## Features

- Camera-based crop scanning using the device camera
- AI diagnosis of plant diseases, pests and nutrient deficiencies
- Treatment and care recommendations
- Runs in the browser, no installation needed

## Tech stack

- React 19, TypeScript and Vite
- Tailwind CSS 4
- Google Gemini API (`@google/genai`)
- Express backend

## Run locally

**Prerequisites:** Node.js

1. Install dependencies:
   ```bash
   npm install
   ```
2. Set `GEMINI_API_KEY` in `.env.local` to your Gemini API key
3. Start the dev server:
   ```bash
   npm run dev
   ```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
