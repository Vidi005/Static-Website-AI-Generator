# Static Website AI Generator
Generate front-end static websites and various web UI components through user prompts or image inputs using Gemini AI.

### App Usage Instructions
Before using this web app, please follow the steps below.
#### Obtaining an API Key:
1. Create an account and log in at <a href="https://ai.google.dev" target="_blank" rel="noopener noreferrer">Google AI Dev Site</a>
2. Select the free tier option
3. Create a project using <a href="https://console.cloud.google.com" target="_blank" rel="noopener noreferrer">Google Cloud Studio</a>
4. Generate an API key within your project
<p align="center">
  <img src="https://github.com/Vidi005/Static-Website-AI-Generator/blob/main/Screenshots/Screenshot-generate-api-key.png" width="100%">
</p>
5. Copy your Gemini API key.
<p align="center">
  <img src="https://github.com/Vidi005/Static-Website-AI-Generator/blob/main/Screenshots/Screenshot-copy.png" width="100%">
</p>

#### Using Static Website AI Generator:
1. Open the Static Website AI Generator Web App in your browser
2. Paste your API key into the designated field
<p align="center">
  <img src="https://github.com/Vidi005/Static-Website-AI-Generator/blob/main/Screenshots/Screenshot-swag.png" width="100%">
</p>
3. Note that prompts entered using the free tier may be utilized by Gemini AI to improve their model quality.

### Web App URLs
- <a href="https://static-website-ai-generator.vercel.app">static-website-ai-generator.vercel.app</a>
- <a href="https://static-website-ai-generator.pages.dev">static-website-ai-generator.pages.dev</a>

### Screenshots
<p align="center">
  <img src="https://github.com/Vidi005/Static-Website-AI-Generator/blob/main/Screenshots/SWAG-1-ezgif.com-optimize.gif" width="100%">
  <img src="https://github.com/Vidi005/Static-Website-AI-Generator/blob/main/Screenshots/SWAG-2-ezgif.com-optimize.gif" width="100%">
</p>

### Features
- Generate static websites from text prompts.
- Generate static websites from both text prompts and image file inputs.
- Dark mode support.
- Localization support (currently available in English and Indonesian).
- Configure AI temperature (randomness) response.
- Select Gemini AI Models.
- Enable/Disable Model Thinking/Reasioning (currently available for Gemini 2.5 Version only).
- Prompt history sidebar (available when the "Save all user data to browser" checkbox is selected).
- Edit the last user input prompt.
- Realtime website preview (accessible from a new tab).
- Realtime generated code preview (HTML, CSS, and JS).
- Copy specific code snippets.
- Export/download generated static website files to your local disk (as a single HTML file or as HTML, CSS, and JS in a compressed ZIP file).
- Reset all user data (including prompt histories and saved Gemini API Key in the browser).

### Tech Stack
- React.js with Vite build tool
- Tailwind CSS
- Headless UI
- Animate.css
- i18next
- jsZIP
- Google AI API
- React Dropzone
- React Drag & Drop
- React Syntax Highlighter
- React Router
- SweetAlert2
- Vite Plugin PWA

### Known Issues
- Candidate was blocked due to RECITATION error results may occur randomly.
<br/>Source: <a href="https://github.com/google-gemini/generative-ai-js/issues/138">Candidate was blocked due to RECITATION bug</a>
