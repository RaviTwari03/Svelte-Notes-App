# Svelte Notes App

A modern, responsive notes application built with Svelte that allows users to create, edit, and manage their notes efficiently.

## Features

- Create and manage notes with a clean, intuitive interface
- Real-time updates and persistence
- Responsive design that works on both desktop and mobile
- Markdown support for rich text formatting
- Local storage for offline functionality

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/RaviTwari03/Svelte-Notes-App.git
cd Svelte-Notes-App
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and navigate to `http://localhost:5000`

## Trade-offs and Assumptions

### Trade-offs
- Used local storage for data persistence instead of a backend database for simplicity and quick setup
- Limited rich text formatting options to maintain a clean and focused user interface
- Prioritized simplicity over complex features to ensure a smooth user experience

### Assumptions
- Users prefer a minimalist interface for note-taking
- Local storage is sufficient for most users' needs
- Users will primarily access the app through modern web browsers

## Future Improvements

Given more time, I would add the following features and improvements:

1. Backend Integration
   - Implement user authentication
   - Add cloud storage for notes
   - Enable note sharing between users

2. Enhanced Features
   - Note categories and tags
   - Search functionality
   - Note export options (PDF, Markdown)
   - Collaborative editing

3. Technical Improvements
   - Add comprehensive test coverage
   - Implement PWA functionality
   - Add offline sync capabilities
   - Optimize performance for large numbers of notes

## License

This project is licensed under the MIT License - see the LICENSE file for details. 