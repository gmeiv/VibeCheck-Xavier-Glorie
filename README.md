# VibeCheck-Xavier-Glorie

## Verayo, Glorie & Uttao, Xavier
## BSCpE 4B
## WEB ENG - Act 3

# VibeCheck 411L

VibeCheck 411L is a fun web app that fetches fortunes, jokes, and mood-based messages from a Node.js backend. 
Users can click buttons to get random fortunes, jokes, or motivational mood messages. 

---

## Features

- Fetch a random fortune.
- Fetch a random joke.
- Get motivational or fun messages based on moods (`happy`, `tired`, `stressed`, etc.).
  

## Run Steps

1. Clone the repository and navigate into it.

2. Go to the backend folder and run npm install.

3. Start the server with node index.js (default: http://localhost:3000).

4. Open frontend/index.html in your browser and click buttons to test.

## API Endpoints

- GET /api/fortune → Returns a random fortune.
- GET /api/joke → Returns a random joke.
- GET /api/vibe?mood=happy|tired|stressed → Returns mood info with emoji and message.
- POST /api/smash → Increments smash counter and returns updated count.
- GET /api/smashes → Returns current smash count.
- GET /api/secret?code=411L → Returns hidden message if code is correct.
