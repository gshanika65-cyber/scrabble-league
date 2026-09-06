# Scrabble League — Full Fresh Build

A full-stack competitive Scrabble League application built from scratch.

## Included

- Landing page
- Real signup/login/logout
- Persistent SQLite database
- Server-side JWT authentication
- Player/Admin roles
- Player profiles and rating history
- Exact 1v1 rating rule: winner +50, loser -10
- Exact 4-player rating rule: 1st +50, 2nd +25, 3rd -10, 4th -20
- Central tier logic: RED → GREEN → BLUE → PURPLE → BLACK → BROWN
- Positions 1–3 always RED
- Real leaderboard
- Real matchmaking queue
- Realtime multiplayer rooms with Socket.IO
- Server-authoritative Scrabble board, rack, bag, turn, validation and scoring
- Full standard tile distribution and values
- Premium-square scoring
- English dictionary validation
- Pass and tile exchange
- AI games with Easy/Medium/Hard move selection
- Persistent tournaments with registration, participants, rounds and results
- Admin dashboard
- Admin player preview mode
- Security checks for roles and competitive mutations
- Responsive desktop/mobile UI
- No seeded fake players, fake ratings, fake match results or fake tournament data

## Run

Node.js 18+ recommended.

```bash
npm install
npm start
```

Open http://localhost:3000

For production, set a strong JWT_SECRET environment variable.
