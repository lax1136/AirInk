✋ AirInk – Write Beyond Boundaries

Touch-Free Digital Drawing Using Hand Gestures

AirInk is an interactive, touch-free drawing application that allows users to draw and manipulate digital strokes using hand gestures captured through a webcam.
Instead of using a mouse, keyboard, or touchscreen, users can use their hands in the air to draw, erase, move, scale, and rotate digital strokes in real time.

✨ Features

🎨 Air Drawing – Draw using your index finger.<br>
✋ Hand Gesture Recognition – Detects hand movements and gestures using real-time hand tracking.<br>
🖐️ Two-Hand Interaction – Use one hand for drawing and another for controlling strokes.<br>
🧹 Erase – Use a pinch gesture to erase nearby strokes.<br>
🗑️ Clear Canvas – Clear the complete drawing using a gesture.<br>
↩️ Undo & Redo – Easily undo or redo drawing actions.<br>
🔄 Move Strokes – Select and reposition strokes using hand gestures.<br>
📐 Scale Strokes – Resize selected strokes using a pinch gesture.<br>
🔃 Rotate Strokes – Rotate selected strokes through hand movement.<br>
🎨 Custom Drawing Settings – Adjust color, line width, and glow intensity.<br>
📷 Camera Controls – Show or hide the camera view.<br>
⚡ Gesture Controls – Enable or disable gesture interaction.<br>
💾 Save Drawings – Download your artwork as a PNG image.<br>
❓ Gesture Guide – Built-in help panel explaining available gestures.<br>
✨ Animated Interface – Interactive UI with smooth visual effects and animations.<br>

🧠 How It Works

Webcam<br>
   ↓<br>
Hand Tracking<br>
   ↓<br>
Hand Landmarks<br>
   ↓<br>
Gesture Interpretation<br>
   ↓<br>
Gesture Detection<br>
   ↓<br>
Drawing / Erasing / Moving / Scaling / Rotating<br>
   ↓<br>
Interactive Canvas<br>

AirInk uses real-time hand landmark detection to understand the position and movement of the user's hands. These landmarks are processed by the gesture interpretation system to identify different gestures and perform the corresponding actions on the canvas.

🖐️ Gesture Controls

Hand<br>
Gesture<br>
Action<br>
Drawing Hand<br>

☝️ Index Finger

Draw<br>
Drawing Hand<br>

🤏 Pinch

Erase nearby strokes<br>
Drawing Hand<br>

✊ Fist

Clear canvas<br>
Control Hand<br>

✌️ Two Fingers

Move strokes<br>
Control Hand<br>

🤏 Pinch

Scale strokes<br>
Control Hand<br>

🖐️ Open Palm + Twist

Rotate strokes

🛠️ Technologies Used

React – Frontend application<br>
Vite – Development server and build tool<br>
JavaScript / JSX – Application logic<br>
MediaPipe Hands – Real-time hand tracking<br>
Framer Motion – UI animations<br>
Tailwind CSS – Styling<br>
Lucide React – Interface icons<br>

📁 Project Structure

AirInk/<br>
│<br>
├── public/<br>
│   ├── favicon.png<br>
│   ├── favicon.svg<br>
│   └── icons.svg<br>
│<br>
├── src/<br>
│   ├── components/<br>
│   │   ├── CameraView.jsx<br>
│   │   ├── ControlPanel.jsx<br>
│   │   ├── DrawingCanvas.jsx<br>
│   │   └── HelpPanel.jsx<br>
│   │<br>
│   ├── modules/<br>
│   │   ├── drawingEngine.js<br>
│   │   ├── gestureController.js<br>
│   │   ├── gestureInterpreter.js<br>
│   │   ├── handTracking.js<br>
│   │   ├── interactionEngine.js<br>
│   │   ├── strokeManager.js<br>
│   │   └── transformEngine.js<br>
│   │<br>
│   ├── App.jsx<br>
│   ├── App.css<br>
│   ├── index.css<br>
│   └── main.jsx<br>
│<br>
├── .gitignore<br>
├── index.html<br>
├── package.json<br>
├── package-lock.json<br>
└── vite.config.js<br>

🚀 Installation & Setup

1. Clone the repository<br>
git clone https://github.com/lax1136/AirInk.git

3. Navigate to the project<br>
cd AirInk

5. Install dependencies<br>
npm install

7. Start the development server<br>
npm run dev

Open the local URL provided by Vite in your browser.

🎮 How to Use

Allow the application to access your webcam.<br>
Raise your hand in front of the camera.<br>
Use your index finger to draw in the air.<br>
Use the supported gestures to erase, clear, move, scale, or rotate strokes.<br>
Customize the drawing color, line width, and glow intensity from the control panel.<br>
Use Undo and Redo whenever needed.<br>
Save your finished drawing as a PNG image.<br>

💡 Why AirInk?

AirInk explores a more natural and touch-free way of interacting with digital drawing tools.<br>
By combining computer vision, hand tracking, and gesture recognition, AirInk transforms hand movements into digital actions, creating an interactive drawing experience without requiring physical input devices.

🔮 Future Enhancements

🔐 User login and authentication<br>
☁️ Cloud storage for drawings<br>
👤 Personal user dashboards<br>
📤 Share drawings through links<br>
🎨 Additional brushes, shapes, and drawing tools<br>
📱 Improved mobile support<br>
🤖 More customizable gestures<br>

👩‍💻 Author

Lakshmi Priya<br>
B.Tech – Artificial Intelligence & Data Science
