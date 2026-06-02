# Handoff Bundle: Liminal Interface Landing Page

This project contains the frontend for the **Liminal Interface** landing page. The goal is to implement a backend to handle the registration form while preserving the existing design.

## Project Structure
- `liminal-interface-landing.html`: The main landing page (Frontend).
- `brand-spec.md`: Brand identity and design tokens.
- `mpwdc35v-image.png`: Brand asset (Cognitive Map).

## Instructions for Gemini CLI

1.  **Understand the Project**: First, read the folder structure and the content of `liminal-interface-landing.html` to understand the form structure (`id="diagnosis-form"`) and the success state logic (`id="success-state"`).
2.  **Backend Implementation ONLY**:
    - Create a Node.js server (e.g., `server.js`) using Express or a similar framework.
    - Use a local JSON file (e.g., `submissions.json`) or a local SQLite database to store form data.
    - **Do NOT** use external databases or cloud services.
3.  **Frontend-Backend Integration**:
    - In `liminal-interface-landing.html`, add a `<script>` or modify the existing one to include an `onSubmit` handler for the form.
    - Use `fetch` to POST the data to your new API endpoint.
    - Handle the UI transition to the `success-state` upon a successful response.
4.  **Preservation Rule**:
    - **Do NOT** modify any existing markup, styles, layout, or class names in `liminal-interface-landing.html`.
    - Retain all visual elements, including the "Interaction Pressure Map" SVG and the clinical diagnostic aesthetic.
5.  **Local Execution**:
    - Ensure the project can be run locally (e.g., `npm start`) so the landing page is accessible at `localhost`.
    - The form must be fully functional from the browser.

## Getting Started
Run `npm install` and then `npm start` (once you have created the backend).
