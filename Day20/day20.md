# Day 20 - AI Face Puzzle Game

## Objective

Build a fully interactive Face Puzzle Game that captures a user's photo through the webcam and converts it into a playable puzzle with multiple difficulty levels.

---

## Focus Area

**AI-Assisted Frontend Development & Interactive Web Applications**

The goal was to create a responsive browser-based puzzle game using modern web technologies while integrating camera access and image processing.

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* Canvas API
* MediaDevices API (getUserMedia)
* LocalStorage

---

## Features Implemented

### Camera Integration

* Webcam access using getUserMedia()
* Live camera preview
* Capture face photo directly in browser
* Graceful handling of camera permission denial

### Puzzle Generation

* Convert captured image into puzzle tiles
* Difficulty selection:

  * 3×3
  * 4×4
  * 5×5
* Randomized tile arrangement

### Drag & Touch Support

* Desktop drag-and-drop controls
* Mobile touch gesture support
* Tile swapping mechanism
* Visual feedback while dragging

### Game Tracking

* Real-time timer
* Move counter
* Correctly placed pieces counter
* Progress tracking

### Win Detection

* Automatic puzzle completion detection
* Results modal
* Final time display
* Move statistics

### Leaderboard

* Top 5 best scores stored using LocalStorage
* Date and difficulty tracking
* Persistent high scores

---

## Application Workflow

Camera Access
↓
Take Photo
↓
Choose Difficulty
↓
Generate Puzzle
↓
Drag & Drop Pieces
↓
Track Progress
↓
Puzzle Complete
↓
Save Score
↓
Leaderboard Update

---

## Key Learnings

* Working with browser camera APIs
* Image manipulation using Canvas
* Puzzle generation logic
* Touch and drag event handling
* State management in JavaScript
* LocalStorage data persistence
* Responsive game UI design

---

## Challenges Faced

* Implementing smooth drag-and-drop interactions
* Supporting both touch and mouse events
* Maintaining puzzle state
* Optimizing performance on mobile devices

---

## Outcome

Successfully built a responsive Face Puzzle Game that transforms a live camera photo into an interactive puzzle experience.

---

## Future Improvements

* Multiplayer mode
* Online leaderboard
* AI-generated puzzle hints
* Animated transitions
* Difficulty auto-adjustment

---

## Conclusion

This project combined camera APIs, image processing, game logic, and responsive design to create a fun and interactive browser-based puzzle application.

