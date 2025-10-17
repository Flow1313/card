# Accessible Responsive Profile Card


A small, accessible, and responsive **Profile Card Component** built using **semantic HTML**, **modern CSS (Flexbox/Grid)**, and **vanilla JavaScript**.  
This component demonstrates best practices in front-end structure, accessibility, responsiveness, and progressive enhancement — with automated testability through `data-testid` attributes

## 🚀 Live Demo on Netlify
(https://chimerical-monstera-01943e.netlify.app/)

## 💻 GitHub Repo
(https://flow1313.github.io/card/profile-card/)

## 🧩 Features
- Semantic HTML5 structure
- Responsive design (Flexbox/Grid)
- Dynamic current time in milliseconds
- Avatar upload + URL preview
- Accessible keyboard navigation
- Social links open in new tabs


## 🧱 Features ✅ Fully responsive layout (mobile, tablet, and desktop) ✅ Semantic HTML5 structure (<article>, <section>, <nav>, <figure>, etc.) ✅ Accessible keyboard navigation and visible focus states ✅ Displays **current time in milliseconds** dynamically ✅ Supports **avatar upload or URL input** ✅ Opens social links in new tabs securely (target="_blank", rel="noopener noreferrer") ✅ Every visible element includes a data-testid for automated testing ✅ Mobile-first CSS layout using Flexbox --- ## 🧭 Project Structure ├── assets/ │ └── (optional images) ├── index.html ├── style.css ├── script.js └── README.md --- ## ⚙️ Run Locally ### Prerequisites You only need a modern web browser — no extra dependencies required. ### Steps 1. Clone the repository:



bash
   git clone https://github.com/Flow1313/card.git



Navigate to the project directory:

cd card



Open the project in your browser:

start index.html
or simply double-click index.html.



🧪 Testing (data-testid attributes)

All elements are discoverable via the following data-testid selectors:

Element	             data-testid
Profile Card Root	    test-profile-card
User Name	          test-user-name
User Bio	             test-user-bio
Current Time	       test-user-time
Avatar Image	       test-user-avatar
Social Links List	    test-user-social-links
Social Item Example	 test-user-social-twitter
Hobbies List	       test-user-hobbies
Dislikes List	       test-user-dislikes



🧩 Accessibility & Responsiveness

Built with semantic HTML5 elements

Keyboard-focusable interactive links

Responsive design for all screen sizes

Mobile-first layout using CSS Flexbox

Alt text provided for all images



🧠 Behavior

Time updates dynamically using Date.now() every second

Avatar preview updates instantly from URL or uploaded image

Layout adjusts automatically on different devices



🧑‍💻 Author

Flow1313

Frontend Developer & IT Support Professional
