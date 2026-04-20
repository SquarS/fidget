🎮 PIDGET — Virtual Interaction Lab
A minimal, sensory-focused web toy built with vanilla HTML/CSS/JS.
No frameworks. No dependencies. Just things that feel satisfying to interact with.
🔗 Live Demo → SquarS.github.io/fidget

Features
WidgetDescription🔴 ClickerA red button with a chrome ring. Click it. That's it. Counts every click with a mechanical sound effect.💡 SwitchA wall light switch that toggles the entire page between dark and light mode. Comes with a satisfying thunk.🌫️ WiperA fogged-up glass pane over a random photo. Drag to wipe it clean. Makes a sandpaper-scratch sound as you go.🎡 WheelScroll the mouse wheel to spin through years, starting from 2026. Each tick makes a mechanical click.🔒 LockA 3-digit combination lock. Drag each dial up or down to change the number. There's a correct combination — find it.

Design Philosophy

No UI noise — dark background, minimal chrome, everything out of the way
Tactile feedback — every interaction has a procedurally generated sound via the Web Audio API
No libraries — pure vanilla JS, zero build steps, opens directly in a browser


Tech Stack

HTML / CSS / JavaScript (Vanilla)
Web Audio API — all sound effects synthesized in real-time, no audio files
Canvas API — fog/wipe effect rendered in real-time


Run Locally
No build process required.
bashgit clone https://github.com/SquarS/fidget.git
cd fidget
# open index.html in your browser
Or just drag index.html into any browser window.

Project Structure
fidget/
├── index.html                              # entire app, single file
├── 1919021-amsterdam-1150319_1920.jpg
├── robert1029-rain-3915684_1920.jpg
├── terbe_rezso-bird-9163532_1920.jpg
└── terbe_rezso-reed-9540853_1920.jpg

License
MIT
