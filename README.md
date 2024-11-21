# Dynamic Form Generator

A React-based dynamic form generator that takes a JSON schema as input and generates a styled, responsive, and functional form in real time. Includes a live JSON editor and preview for an interactive experience.

---

## Features
- Live JSON Editor:
  - Syntax highlighting.
  - Real-time JSON validation.
  - Error messages for invalid JSON.
- Dynamic Form Preview:
  - Updates instantly based on JSON schema.
  - Supports various field types (text, email, textarea, select, radio).
  - Form validation with feedback messages.
- Mobile Responsive:
  - Split-screen layout on larger screens.
  - Stacked layout on smaller screens.
- User Experience Enhancements:
  - Loading states for actions.
  - Success messages after form submission.

---

## Technologies Used
- Frontend: React 18+, React Hook Form, TypeScript
- Styling: Tailwind CSS
- Testing: Jest, Playwright
- Build Tool: Vite (optional)

---

## Getting Started

### Prerequisites
Ensure the following tools are installed:
- Node.js (v16+)
- npm or yarn
- A code editor like VS Code

---

### Installation
1. Clone the repository:
   git clone <repository-url>
   cd dynamic-form-generator
2. Install dependencies:
   npm install

---

### Usage

1. Start the development server:
   npm start
2. Open the app in your browser at http://localhost:3000.

---

### Build for Production
To create an optimized build:
npm run build

The production-ready files will be located in the `build/` directory.

---

### Testing

Unit Testing with Jest:
npm test

End-to-End Testing with Playwright:
npx playwright test

---

## Folder Structure
