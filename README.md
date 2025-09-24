Real-Time Code Editor

A collaborative real-time code editor built with React, Node.js, and Socket.IO, enabling multiple users to write and edit code simultaneously.

🚀 Features

Live Collaboration: Multiple users can join a room and edit code in real-time.

Syntax Highlighting: Supports various programming languages with syntax highlighting.

Code Synchronization: Changes made by one user are instantly reflected for all users in the room.

User Presence: Displays a list of connected users in the room.

Room Management: Users can create and join rooms using unique room IDs.

🛠️ Technologies Used

Frontend: React, React Router, Recoil (for state management)

Backend: Node.js, Express, Socket.IO

Code Editor: CodeMirror

Styling: CSS, CodeMirror themes

📁 Project Structure
real-time-code-editor/
├── client/                  # React frontend
│   ├── components/          # React components
│   ├── App.js               # Main application component
│   ├── index.js             # Entry point for React
│   └── ...
├── backend/                 # Node.js backend
│   ├── server.js            # Express server with Socket.IO
│   └── ...
├── package.json             # Project metadata and dependencies
└── README.md                # Project documentation

🔧 Installation
1. Clone the repository
git clone https://github.com/Ravipujar0055/real-time-code-editor.git
cd real-time-code-editor

2. Install dependencies for both client and backend
Client
cd client
npm install

Backend
cd backend
npm install

3. Run the application
Start the backend server
cd backend
npm start

Start the frontend development server
cd client
npm start


The application should now be running at http://localhost:3000.

🧪 Usage

Open the application in multiple tabs or different browsers.

Create a new room or join an existing room using the room ID.

Start coding! Changes made by one user will be reflected in real-time for all users in the room.
