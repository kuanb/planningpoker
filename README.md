# Planning Poker

Peer-to-peer planning poker for estimating ticket sizes on a call. No backend — runs entirely in the browser using WebRTC via PeerJS.

## How it works

1. One person creates a room and shares the 5-character code
2. Others join with the code
3. Everyone picks a Fibonacci estimate (0, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ?, or coffee break)
4. Hit **Reveal** to show all votes and see average/mode/range
5. Hit **Reset** to start the next ticket

## Deploy

Hosted via GitHub Pages — just a single `index.html`, no build step.
