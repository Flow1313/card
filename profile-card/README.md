# 🌟 Accessible Multi-Page Profile Card Project (Stage 1)

This project builds upon the **Stage 0 Profile Card**, expanding it into a **multi-page, accessible, and responsive web application**.  
It includes a **Home (Profile Card)**, **About Me**, and **Contact Us** page — all built with semantic HTML, modern CSS, and vanilla JavaScript.

## 🚀 Live Demo on Netlify
(https://chimerical-monstera-01943e.netlify.app/)

## 💻 GitHub Repo
(https://flow1313.github.io/card/profile-card/)


## 🗂️ Project Structure

profile-card/
├── index.html # Home page – Profile Card
├── about.html # About Me page
├── contact.html # Contact Us page (with validation)
├── style.css # Shared responsive styles
├── script.js # Main JS + contact form validation
└── README.md # Project documentation

markdown
Copy code

---

## 🏠 Home Page (`index.html`)
Displays a responsive **Profile Card** featuring:

- User avatar (upload or URL input)
- Name and bio
- Real-time clock
- Social links (Twitter, LinkedIn, GitHub)
- Hobbies and dislikes
- Semantic and accessible HTML5 structure
- Data-test IDs for automated testing

**Accessibility features:**
- Proper `<header>`, `<main>`, `<section>` use  
- `alt` and `aria-label` attributes for clarity  
- Keyboard-friendly navigation  

---

## 👤 About Me Page (`about.html`)

Reflective page describing personal insights and learning journey.

**Required Sections (each with `data-testid`):**
- `test-about-bio` → Bio  
- `test-about-goals` → Goals in this program  
- `test-about-confidence` → Areas of low confidence  
- `test-about-future-note` → Note to future self  
- `test-about-extra` → Extra thoughts  

**Semantic HTML:**
- Wrapped in `<main data-testid="test-about-page">`
- Each topic inside its own `<section>` with clear headings

---

## 📩 Contact Us Page (`contact.html`)

A simple, accessible contact form with JavaScript validation.

**Fields (all required):**
- Full Name → `test-contact-name`  
- Email → `test-contact-email`  
- Subject → `test-contact-subject`  
- Message → `test-contact-message`  
- Submit Button → `test-contact-submit`  

**Validation Rules:**
- All fields required  
- Valid email format (`name@example.com`)  
- Message must be at least 10 characters  
- Error messages tied with `aria-describedby` and  
  IDs like `test-contact-error-email`  
- Success message → `test-contact-success` (shows only after valid submission)

---

## 💻 Accessibility & Responsiveness

- Built with semantic HTML5  
- Fully keyboard navigable  
- WCAG-aligned labeling  
- Works on mobile, tablet, and desktop (flex/grid layout)  
- High color contrast and visible focus states  

---

## ⚙️ Technologies Used
- HTML5  
- CSS3 (Flexbox, Grid, Media Queries)  
- Vanilla JavaScript (DOM Manipulation & Validation)

---

## 📜 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
Open index.html in your browser or use a live server:

bash
Copy code
npx serve
Explore the pages:

/index.html → Home (Profile Card)

/about.html → About Me

/contact.html → Contact Us

📝 Submission
Submission Link: https://forms.gle/J65RPCVspzJJDGNP7

Submit:

✅ Live hosted URL

✅ GitHub repo link with full code and README

✨ Author
Name: Bello Ibrahim
Role: Frontend Developer / IT Support Professional
Email: talk2ibb2003@gmail.com
GitHub: flow1313



