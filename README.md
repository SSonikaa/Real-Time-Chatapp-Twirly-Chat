<h1>💬 Twirly Chat App</h1>

<p>
  <strong>Twirly</strong> is a real-time full-stack chat application built using the <strong>MERN stack</strong> (MongoDB, Express.js, React, Node.js) 
  and <strong>Socket.IO</strong> for real-time communication. The app enables seamless one-on-one messaging with live status indicators, 
  notifications, and a responsive UI for a smooth user experience.
</p>

<p>
  It’s designed to simulate a modern-day messaging platform where users can log in, send messages instantly, get notified in real time, 
  and track online users. Twirly offers a secure login system, intuitive interface, and real-time engagement through websockets.
</p>

<p>
  🔗 <strong>View it live:</strong> <a href="https://twirlychat.onrender.com" target="_blank">https://twirlychat.onrender.com</a>
</p>


<h2>✨ Features</h2>

<h3>🔐 Authentication</h3>
<ul>
  <li>Secure user registration and login</li>
  <li>Password encryption using bcrypt</li>
  <li>Logout support with JWT token clearance</li>
</ul>

<h3>📡 Real-Time Chat</h3>
<ul>
  <li>Instant messaging via Socket.IO</li>
  <li>Online/offline user status indicators</li>
  <li>Typing notifications (optional feature)</li>
</ul>

<h3>🔔 Notifications</h3>
<ul>
  <li>Real-time message alerts</li>
  <li>Optional sound or visual notification settings</li>
</ul>

<h3>🧑‍🤝‍🧑 User Management</h3>
<ul>
  <li>Displays list of online users</li>
  <li>Chat initiation with any active user</li>
</ul>

<h3>💻 UI/UX</h3>
<ul>
  <li>Clean, responsive, and mobile-friendly interface</li>
  <li>Dynamic updates without page reloads</li>
  <li>Optional dark/light mode support</li>
</ul>



<h2>🛠️ Tech Stack</h2>
<ul>
  <li><strong>Frontend:</strong> React, CSS, Axios</li>
  <li><strong>Backend:</strong> Node.js, Express.js</li>
  <li><strong>Database:</strong> MongoDB (with Mongoose)</li>
  <li><strong>Real-Time Communication:</strong> Socket.IO</li>
  <li><strong>Authentication:</strong> JWT (JSON Web Token), bcrypt</li>
</ul>


<h2>📸 Screenshots</h2>

Login:

![Screenshot (22)](https://github.com/user-attachments/assets/6b5c0bbe-2287-4fc3-89b7-43ebd381b391)


Signup


![Screenshot (24)](https://github.com/user-attachments/assets/64e2cf23-fe15-4264-8b76-9dbc0354992e)



Chat:

![Screenshot (23)](https://github.com/user-attachments/assets/380506ef-9b33-4d8c-9c5d-9b236cbf21ec)


<hr/>
<h2>🚀 Getting Started</h2>

<h3>1. Clone the repository</h3>
<pre><code>git clone https://github.com/ssonikaa/Real-Time-Chatapp-Twirly-Chat.git
cd twirly-chat-app</code></pre>

<h3>2. Backend Setup (Server)</h3>
<pre><code>cd server
npm install
# Create a .env file with your MongoDB URI and JWT secret
npm start</code></pre>

<h3>3. Frontend Setup (Client)</h3>
<pre><code>cd client
npm install
npm start</code></pre>

<h2>📂 Project Structure</h2>
<pre><code>twirly-chat-app/
├── client/               # React frontend
│   └── src/
├── server/               # Node.js + Express backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── socket.js
└── README.html
</code></pre>


<h2>📦 Future Enhancements</h2>
<ul>
  <li>Group chat and broadcast messaging</li>
  <li>File and media sharing</li>
  <li>Read receipts and message delivery status</li>
  <li>Chat history search and filtering</li>
</ul>



<h2>🙌 Credits</h2>
<p>
  Built by <strong>Sonika</strong><br/>
  </p>


