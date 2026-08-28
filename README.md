✋ AirInk – Write Beyond Boundaries

Touch-Free Digital Drawing Using Hand Gestures
AirInk is an interactive, touch-free drawing application that allows users to draw and manipulate digital strokes using hand gestures captured through a webcam.
Instead of using a mouse, keyboard, or touchscreen, users can use their hands in the air to draw, erase, move, scale, and rotate digital strokes in real time.
✨ Features
🎨 Air Drawing – Draw using your index finger.
✋ Hand Gesture Recognition – Detects hand movements and gestures using real-time hand tracking.
🖐️ Two-Hand Interaction – Use one hand for drawing and another for controlling strokes.
🧹 Erase – Use a pinch gesture to erase nearby strokes.
🗑️ Clear Canvas – Clear the complete drawing using a gesture.
↩️ Undo & Redo – Easily undo or redo drawing actions.
🔄 Move Strokes – Select and reposition strokes using hand gestures.
📐 Scale Strokes – Resize selected strokes using a pinch gesture.
🔃 Rotate Strokes – Rotate selected strokes through hand movement.
🎨 Custom Drawing Settings – Adjust color, line width, and glow intensity.
📷 Camera Controls – Show or hide the camera view.
⚡ Gesture Controls – Enable or disable gesture interaction.
💾 Save Drawings – Download your artwork as a PNG image.
❓ Gesture Guide – Built-in help panel explaining available gestures.
✨ Animated Interface – Interactive UI with smooth visual effects and animations.
🧠 How It Works
Webcam
   ↓
Hand Tracking
   ↓
Hand Landmarks
   ↓
Gesture Interpretation
   ↓
Gesture Detection
   ↓
Drawing / Erasing / Moving / Scaling / Rotating
   ↓
Interactive Canvas
AirInk uses real-time hand landmark detection to understand the position and movement of the user's hands. These landmarks are processed by the gesture interpretation system to identify different gestures and perform the corresponding actions on the canvas.
🖐️ Gesture Controls
Hand
Gesture
Action
Drawing Hand
☝️ Index Finger
Draw
Drawing Hand
🤏 Pinch
Erase nearby strokes
Drawing Hand
✊ Fist
Clear canvas
Control Hand
✌️ Two Fingers
Move strokes
Control Hand
🤏 Pinch
Scale strokes
Control Hand
🖐️ Open Palm + Twist
Rotate strokes
🛠️ Technologies Used
React – Frontend application
Vite – Development server and build tool
JavaScript / JSX – Application logic
MediaPipe Hands – Real-time hand tracking
Framer Motion – UI animations
Tailwind CSS – Styling
Lucide React – Interface icons
📁 Project Structure
AirInk/
│
├── public/
│   ├── favicon.png
│   ├── favicon.svg
│   └── icons.svg
│
├── src/
│   ├── components/
│   │   ├── CameraView.jsx
│   │   ├── ControlPanel.jsx
│   │   ├── DrawingCanvas.jsx
│   │   └── HelpPanel.jsx
│   │
│   ├── modules/
│   │   ├── drawingEngine.js
│   │   ├── gestureController.js
│   │   ├── gestureInterpreter.js
│   │   ├── handTracking.js
│   │   ├── interactionEngine.js
│   │   ├── strokeManager.js
│   │   └── transformEngine.js
│   │
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
│
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
└── vite.config.js
🚀 Installation & Setup
1. Clone the repository
git clone https://github.com/lax1136/AirInk.git
2. Navigate to the project
cd AirInk
3. Install dependencies
npm install
4. Start the development server
npm run dev
Open the local URL provided by Vite in your browser.
🎮 How to Use
Allow the application to access your webcam.
Raise your hand in front of the camera.
Use your index finger to draw in the air.
Use the supported gestures to erase, clear, move, scale, or rotate strokes.
Customize the drawing color, line width, and glow intensity from the control panel.
Use Undo and Redo whenever needed.
Save your finished drawing as a PNG image.
💡 Why AirInk?
AirInk explores a more natural and touch-free way of interacting with digital drawing tools.
By combining computer vision, hand tracking, and gesture recognition, AirInk transforms hand movements into digital actions, creating an interactive drawing experience without requiring physical input devices.
🔮 Future Enhancements
🔐 User login and authentication
☁️ Cloud storage for drawings
👤 Personal user dashboards
📤 Share drawings through links
🎨 Additional brushes, shapes, and drawing tools
📱 Improved mobile support
🤖 More customizable gestures
👩‍💻 Author
Lakshmi Priya
B.Tech – Artificial Intelligence & Data Science
