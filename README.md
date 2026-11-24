# AgroCare

A crop-diagnosis prototype built by Team Tech Titans, with rule-based guidance and experimental Gemini-powered features.

AgroCare turns a phone or laptop camera into a crop doctor. Capture a photo of an affected plant and the app analyzes it with Google's Gemini model to identify likely diseases, pests or deficiencies, then suggests treatment steps.

## Prototype status

AI calls currently run in the browser. Do not publish this version with a real Gemini key; move those calls to a protected server first.

## Features

- Camera-based crop scanning using the device camera
- AI diagnosis of plant diseases, pests and nutrient deficiencies
- Treatment and care recommendations
- Runs in the browser, no installation needed

## Tech stack

- React 19, TypeScript and Vite
- Tailwind CSS 4
- Google Gemini API (`@google/genai`)

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
