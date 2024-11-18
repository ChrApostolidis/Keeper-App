# Keeper-App

Keeper App is a simple React-based note-taking application inspired by Google Keep. It allows users to create, view, and delete notes dynamically. This project showcases core React concepts, Material-UI integration, and responsive design for an intuitive user experience.

## Features
* Dynamic Note Creation: Add notes with a title and content.
* Delete Notes: Remove any note from the list.
* Responsive Input Form: Expands the input area dynamically when focused.
* Material-UI Integration: Styled using Material-UI icons and components.
* Responsive Design: Adjusts form layout based on user interaction.

Installation and Setup

Clone the Repository
```
git clone https://github.com/yourusername/keeper-app.git
cd keeper-app
```
Install Dependencies
```
npm install
```
Run the Application

```
npm start
```

### File Structure
* /components
    * App.jsx: Main application component, manages state and renders other components.
    * Header.jsx: Displays the app's header with a logo.
    * Footer.jsx: Displays the footer with the current year.
    * Note.jsx: Represents individual notes with delete functionality.
    * CreateArea.jsx: Contains the form for creating new notes.
* /styles.css: Custom styles for app layout.

### How It Works
1. Adding Notes:
    * Click on the text area to expand the input form.
    * Enter a title and content, then click the "+" button to add the note.
2. Viewing Notes:
    * All notes are displayed below the input form in a card format.
3. Deleting Notes:
    * Click the trash icon on a note to remove it.