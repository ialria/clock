🕒 JavaScript Analog Clock

A modern real-time analog clock built using **HTML, CSS, and Vanilla JavaScript**.  
It displays the current time using rotating hour, minute, and second hands with smooth animations and a clean glassmorphism UI design.

Live Features

- 🕰️ Real-time clock updates every second  
- 🧠 Uses JavaScript `Date()` object  
- 🎯 Smooth rotation for all clock hands  
- 🎨 Modern glassmorphism UI design  
- ⚡ Pure HTML, CSS, and JavaScript (no libraries)  
- 🔁 Handles smooth transitions and reset issues  

 How It Works

- JavaScript gets current time using `new Date()`
- Seconds, minutes, and hours are converted into degrees
- Each hand is rotated using CSS `transform: rotate()`
- `setInterval()` updates the clock every second
- Special logic prevents jumpy animation when values reset (like 59 → 0)

Technologies Used

- HTML5 (structure)
- CSS3 (styling + glass effect)
- JavaScript (logic + time handling)

 ▶️ How to Run

1. Download or clone the project  
2. Open `index.html` in any browser  
3. The clock will start automatically  

No installation required.

 What I Learned

- Working with JavaScript Date object  
- DOM manipulation  
- CSS transforms and animations  
- Real-time updates using setInterval  
- UI design with glassmorphism effect  
