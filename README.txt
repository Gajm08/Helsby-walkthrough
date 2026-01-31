Helsby Road – Phone Walkthrough

How to run (phone-friendly):

Option A (easiest): host as a tiny website
1) Upload this folder to any static host (Netlify, Vercel, GitHub Pages, etc.)
2) Open the site on your phone.
3) Use the left joystick to move, right joystick to look around.
4) Use the Ground / Upstairs buttons to switch floors.

Option B: run locally on a computer and open from your phone on the same Wi‑Fi
1) Put this folder somewhere on your computer.
2) Start a simple server in this folder, e.g.:
   - Python:  python -m http.server 8000
3) On your phone, open: http://YOUR_COMPUTER_IP:8000

Notes
- This model is generated from the floorplan image (walls as extruded “pixels”) plus auto-placed generic furniture.
- If you want furniture to match the photos exactly (sofa style, bed sizes, kitchen units, etc.), the next step is: room-by-room furniture list OR a few key measurement anchors.
