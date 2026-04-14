📂 Project: The 2026 Protocol Simulation
An Interactive Strategic Training Environment

🎯 Project Overview
The 2026 Protocol is a web-based, interactive "Escape Room" simulation designed to train public health professionals and service technicians on emerging synthetic threats and organizational shifts.

By navigating three distinct virtual environments, users must apply situational awareness and collaborative problem-solving to identify threats, execute response frameworks, and establish stability bridges.

🏛️ Strategic Framework: The Pillars
The simulation is built on the concept of Strategic Pillars—foundational competencies required for a functioning 2026 public health system:

Vigilance (Room 1): Identification of high-potency synthetics (e.g., Medetomidine).

Response (Room 2): Operationalizing immediate life-saving protocols (e.g., Repeat Dosing).

Connection (Room 3): Establishing "Warm Handoffs" and low-barrier telehealth links.

Resilience (Final Room): The integration of all three pillars to reach system stability.

👥 Collaborative Mechanics: Team Roles
To encourage teamwork in a remote or breakout-room setting, the simulation utilizes a dual-role system:

The Navigator: Responsible for screen-sharing and tactical exploration of the environments.

The Cluemaster: Responsible for documentation and recording the "Pillar Log" for final system activation.

🛠️ Technical Architecture
Frontend: HTML5 / CSS3 / JavaScript (Vanilla).

Responsive Design: Utilizes a "Contain and Center" logic to ensure a proportional, non-distorted experience across both high-resolution desktops and mobile devices.

Logic: Percentage-based hotspot mapping to ensure interactive elements scale perfectly with the background assets.

Security: Implements a Caesar Cipher (ROT-3) for the final decryption phase to test cognitive recall and problem-solving.

🎨 Customization & Reuse
This project is built as a reusable template. To adapt this for other college courses or professional scenarios:

1. Swapping Environments
Replace the image files in the root directory (room1.png, room2.png, room3.jpg, final.png) with new assets. The code will automatically center and scale the new images.

2. Updating Passwords
In the <script> section of each HTML file, locate the checkAnswer() function and update the string value:

JavaScript
if(val === 'NEW_PASSWORD') { ... }
3. Adjusting the Cipher
In final.html, the cipher is set to a "Backward 3" shift. To change the difficulty or the word:

Update the displayed cipher text: Change <div class="cipher-text">UHVLOLHQFH</div>.

Update the logic: Adjust the if (key === 'RESILIENCE') check to your new word.

🏁 The "Cheat Sheet" (Instructor Key)
Room 1 (The Lab): Word = MEDETOMIDINE | Pillar = VIGILANCE

Room 2 (The Hub): Word = REPEAT | Pillar = RESPONSE

Room 3 (The Handoff): Word = CONNECT | Pillar = CONNECTION

Final Room (The Cipher): Decrypted Word = RESILIENCE (Shifted backward by 3).

🚀 Deployment
This project is optimized for GitHub Pages.

Push all files to a GitHub repository.

Go to Settings > Pages.

Select the main branch and click Save.

🎓 Academic Note:
This project demonstrates proficiency in Instructional Design, Responsive Web Development, and Strategic Communications. It bridges the gap between technical execution and public health advocacy, providing a scalable model for remote workforce development.

*** Project Developed by: Dr. E Willis
Last Updated: April 2026
