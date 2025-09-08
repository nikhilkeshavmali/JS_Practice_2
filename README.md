🎯 GSAP Rectangle Mouse Tracker

This project demonstrates how to animate a rectangle (div) that follows your mouse movement smoothly using GSAP (GreenSock Animation Platform).

🚀 Features

Red rectangle centered on the screen.

Smooth horizontal animation based on mouse movement.

Uses GSAP mapRange utility for mapping mouse position to rectangle position.

Responsive and lightweight.

🖼️ Demo Screenshot

<img width="1918" height="867" alt="image" src="https://github.com/user-attachments/assets/1931f345-71eb-4e87-b1f5-0a6dc5c4bc68" />


📂 Project Structure
.
├── index.html      # Main HTML file
├── styles.css      # CSS for styling
├── script.js       # JavaScript + GSAP animation logic

🛠️ Technologies Used

HTML5

CSS3

JavaScript (ES6)

GSAP 3.13.0

📜 Code Explanation
HTML (index.html)

Includes GSAP via CDN.

Contains a single div with ID rect.

CSS (styles.css)

Styles the rectangle (200px x 300px, red color).

Centers it using position: absolute + transform.

JavaScript (script.js)

Listens to mousemove event.

Uses gsap.utils.mapRange to convert mouse X position → rectangle’s left position.

Animates rectangle with gsap.to and "power3.out" easing.

▶️ How to Run

Clone this repo:

git clone https://github.com/your-username/gsap-rectangle-tracker.git
cd gsap-rectangle-tracker


Open index.html in your browser.

🎯 Output

Move your mouse left ↔ right → rectangle moves smoothly in sync.

📌 Future Improvements

Add vertical tracking (Y-axis movement).

Add hover effects or scaling animations.

Add different shapes or colors for interaction.
