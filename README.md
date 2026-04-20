FrameCalc
A lightweight web-based tool for converting between milliseconds and frames at any professional framerate.
No installation, no download — it runs directly in your browser.
Live tool: https://stage-tools.github.io/framecalc/
---
Features
Bidirectional conversion — edit milliseconds or frames, the other side updates live
9 standard framerate presets — 23.976, 24, 25, 29.97, 30, 48, 50, 59.94, 60 fps
Custom framerate input for non-standard workflows
Reference panel showing active FPS, duration of one frame, and a live timecode preview (HH:MM:SS:FF)
Persistent settings — the last used framerate is remembered between sessions
Fully client-side — no server, no tracking, no data leaves your browser
---
Use cases
Audio / video post-production
Live show programming and cue timing
Animation frame budgeting
SMPTE timecode reference work
Any workflow that needs quick conversion between time and frame counts
---
How to use
Select a framerate from the presets (or type a custom value)
Enter a value in either the Milliseconds or Frames field
The other value updates automatically
The Reference panel shows the equivalent timecode and per-frame duration
---
Technical notes
Pure HTML + CSS + JavaScript, single file, zero dependencies
Works offline once the page is loaded
Timecode display is non-drop frame (visual reference only)
29.97 fps and 30 fps produce different results for the same millisecond value — this is correct behaviour
---
Version
v0.1.0 — Initial release
---
Author
Made by Riccardo Nessi
