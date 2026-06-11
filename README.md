# 3d-tilt-cards
# 3D Tilt Testimonials Page

A simple and interactive testimonials page featuring a cool 3D tilt effect and a mouse-tracking glow effect. I built this using pure HTML, CSS, and Vanilla JavaScript to practice DOM manipulation and 3D transforms.
---
 🚀 Features
* 3D Hover Effect: The cards rotate dynamically based on your mouse movement.
* Mouse-Tracking Glow: A smooth radial gradient glow follows your cursor inside each card.
* Fully Responsive: Used CSS Grid `auto-fit`, so it automatically adjusts to mobile and desktop screens without a ton of media queries.
* No Frameworks: Built purely with Vanilla JS and CSS—no React or heavy libraries needed.
---
 🛠️ Tech Used
* HTML5– Page layout and structure
* CSS3– Grid, `preserve-3d` transforms, and custom variables
* JavaScript– Mouse move event listeners and coordinate tracking
* FontAwesome– For the quote icons
---
## 🧠 How It Works
1. Getting Coordinates: I used `getBoundingClientRect()` to fetch the card's exact position and size on the screen.
2. Mouse Position Math: Calculated where the mouse is pointing inside the card by subtracting the card's left and top offsets from the cursor's global coordinates (`e.clientX` and `e.clientY`).
3. Applying Effects: Used that math to calculate the rotation angles. Then, I updated the CSS `transform` property on the fly and passed the X/Y coordinates to CSS variables (`--x`, `--y`) to move the background glow.
---
⚙️ How to Run Locally
Just clone the repo and open the `index.html` file in any browser:
```bash
# Clone the repository
git clone https://github.com/srivastavaamishka-glitch/3d-tilt-cards.git
# Go into the project folder
cd 3d-tilt-cards
```
