# m-games
This is the Website for games for family and friends 
Project Name (suggested): GameMingle (or choose your own)

Objective:
Build a real-time web application where users can play simple, fun, social games like Truth or Dare, Would You Rather, Never Have I Ever, and other classic party games with friends online.

Core Features:

🧑‍🤝‍🧑 User Authentication – Sign up, login, guest mode

🕹️ Game Lobby System – Create/join game rooms, invite friends

🗨️ Live Chat Integration – In-room text chat during games

♻️ Turn-Based Game Logic – Real-time syncing of game state

🔀 Game Modules – Multiple party games (Truth or Dare, etc.)

📊 Game History – Optional tracking of sessions or scores

💡 Custom Prompts – Users can add or vote on new questions

Technology Stack:

Frontend: React.js, Tailwind CSS / Bootstrap, Socket.IO (for real-time)

Backend: Node.js + Express (for lobby & game logic), Django (for user mgmt, admin panel, analytics)

Database: MongoDB (game sessions, prompts), PostgreSQL (users, history)

Realtime: Socket.IO / Django Channels

Hosting: Vercel/Netlify (frontend), Heroku/Render (backend), MongoDB Atlas

Stretch Goals:

🧠 AI-generated prompts using GPT API

📱 Responsive mobile UI

🎨 Dark/light mode

🎉 Public party rooms with moderation

📹 Optional video/voice (WebRTC)