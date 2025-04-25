YouTube Looper - README

Project Title: YouTube Looper
Author: Jack Reak
GitHub: https://github.com/jackreak
File: YTLooper.html
License: MIT (see included LICENSE file)

---------------------------------------
📌 Overview
---------------------------------------
YouTube Looper is a lightweight, single-page web app that allows you to:
✔️ Embed any public YouTube video
✔️ Select custom start and stop points using intuitive sliders
✔️ Automatically loop a specific segment of the video
✔️ Use full multimedia playback controls
✔️ Enjoy a clean, professional interface designed for desktop use

Whether you're looping a song, a meme, or practicing a part of a tutorial, this tool makes it effortless to zero in on what you want.

---------------------------------------
🚀 How to Use
---------------------------------------
1. Open the file `YTLooper.html` in any modern desktop web browser (Chrome, Firefox, Edge, etc.).
2. Paste a **YouTube video URL** or a **video ID** into the input box.
   - Examples:
     - Full URL: https://youtu.be/cEHP_LeBeyQ
     - Video ID: cEHP_LeBeyQ
3. Click "Load Video" to embed the video player.
4. After the video loads:
   - Use the **Start** and **End** sliders below the player to define the loop segment.
   - The video will automatically jump to the start time after reaching the end time, looping continuously.
5. You can adjust the loop range at any time, or input a new video.

Note: This app is designed for **desktop use only** at this time. It might work on mobile. Frankly, I haven't even tried.

---------------------------------------
⚠️ Limitations & Notes
---------------------------------------
- Some videos may not load due to:
  - Copyright restrictions
  - Age restrictions
  - Regional availability
  - Embedding disabled by the uploader
- In those cases, you’ll see a “Video Unavailable” message.
- This app uses the **YouTube IFrame Player API**, so it requires an internet connection.

---------------------------------------
🎨 Customization & Styling
---------------------------------------
- The layout is styled for clarity and ease of use.
- Sliders are styled with contrast and tooltips for accessibility.
- If you wish to change the look and feel, modify the embedded CSS in the `<style>` section of `index.html`.

---------------------------------------
🔧 Technologies Used
---------------------------------------
- HTML5
- CSS3
- Vanilla JavaScript (ES6)
- YouTube IFrame API

---------------------------------------
📂 File Structure
---------------------------------------
- YTLooper.html      => The entire app is contained in this file
- LICENSE    => If using an open-source license like MIT

---------------------------------------
💬 Feedback & Contributions
---------------------------------------
If you enjoy this tool or want to contribute:
🌐 GitHub: https://github.com/jackreak

Feel free to fork, improve, and suggest new features through issues or pull requests.

---------------------------------------
📜 License
---------------------------------------
MIT License. Free to use, modify, and distribute with attribution.

Copyright (c) 2025 Jack Reak

---------------------------------------
