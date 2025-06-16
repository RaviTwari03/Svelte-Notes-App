# Svelte Notes App

A minimalist note-taking application built with Svelte and Vite, focusing on simplicity and ease of use.

## How to Run the App

1. Clone the repository:
```bash
git clone https://github.com/RaviTwari03/Svelte-Notes-App.git
cd Svelte-Notes-App
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to the URL shown in your terminal (typically `http://localhost:5173`)

## Trade-offs & Assumptions

### Trade-offs Made
- Used Vite instead of SvelteKit for simpler setup and faster development iteration
- Implemented client-side only storage for quick prototyping
- Focused on core note-taking features over additional functionality
- Minimalist UI to reduce complexity and improve user focus

### Assumptions
- Users need a straightforward, no-frills note-taking experience
- Local storage is sufficient for initial MVP
- Modern browser support is acceptable
- Single-user usage (no multi-user support needed initially)

## Future Improvements

Given more time, I would add:

1. Core Features
   - Note search and filtering
   - Categories/tags for organization
   - Rich text editing
   - Note sharing capabilities

2. Technical Enhancements
   - Backend API integration
   - User authentication
   - Cloud storage sync
   - Offline support
   - Automated testing
   - Performance optimizations

3. UX Improvements
   - Dark mode support
   - Keyboard shortcuts
   - Drag-and-drop organization
   - Mobile-optimized interface
