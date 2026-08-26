Interactive GPA Calculator
A lightweight, single-file GPA calculator built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies — just open and use.
https://animated-gpa-calculator.vercel.app/


Features

Real-time GPA calculation using a weighted credit system
Subject-aware animations that trigger based on the subject name entered:

Physics / Electronics — energy dot traveling along a wire to a light bulb
Mathematics / Statistics — rotating 3D wireframe cube
Computer Science / Programming — glitch-effect </> symbol
Networks / AI / Databases — animated circuit board with drawing lines and nodes
Chemistry — bubbling test tube that fills with liquid
Biology — pulsing SVG leaf with vein detail
Software Engineering / HCI / Mobile Dev — animated C and V keyboard keys


Grade-based color theming — each grade (S through F) has a distinct glow color applied across all animations
Dynamic card management — add and delete subject cards on the fly
GPA pulse animation on every recalculation
Sticky header and fixed GPA display panel


Getting Started
bashgit clone https://github.com/your-username/gpa-calculator.git
cd gpa-calculator
open index.html
No build step or install required. Works directly in any modern browser.

Grade Point Scale
GradePointsS10A9B8C7D6E5F0
Formula: GPA = sum(Grade Points x Credits) / sum(Credits)

Project Structure
gpa-calculator/
└── index.html      # All markup, styles, and logic in a single file

Customization

Subject keywords and animations — edit the subjectAnimations array to add or reassign keyword-to-animation mappings
Grade colors and glows — update the gradeColors and gradeGlows objects
New animation types — add a case to the playAnimation() switch and a corresponding create*() function


Browser Support
Compatible with all modern browsers (Chrome, Firefox, Edge, Safari). Uses standard CSS animations, SVG, and the Web Animations API — no polyfills needed.
