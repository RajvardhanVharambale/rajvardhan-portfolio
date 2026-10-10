# Rajvardhan Vharambale — Personal Portfolio Website

A personal portfolio website showcasing my background, technical skills, projects, education, and extracurricular experience as a Computer Science and Engineering student.

The website is built using **HTML5, CSS3, and JavaScript** with a responsive layout, smooth navigation, and a dark navy-blue visual theme.

---

## 📌 Project Overview

This portfolio introduces me, highlights my technical interests, and provides a way for visitors to connect with me professionally.

### Objectives

- Create a personal website to present my profile and skills.
- Showcase my software development projects.
- Display my academic background and achievements.
- Highlight leadership, volunteering, and campus involvement.
- Provide contact information and an interactive contact form.
- Practise semantic HTML, responsive CSS, and JavaScript.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and semantic content |
| CSS3 | Styling, layout, colors, animations, and responsiveness |
| JavaScript | Mobile navigation, reveal animations, footer year, and contact form |
| VS Code | Code editor |
| Git and GitHub | Version control and project hosting |

**No framework, package manager, or backend server is required** to run this static portfolio website.

---

## ✨ Website Features

- Responsive layout for desktop, tablet, and mobile screens.
- Sticky navigation bar with internal section links.
- Introduction section with profile image.
- About section with academic information and personal goals.
- Skills section covering programming, frontend development, tools, and people skills.
- Projects section featuring CodeVault, APEXA, and Java Text Editor.
- Education section listing academic qualifications.
- Experience section featuring placement coordination, student initiatives, and volunteering.
- Contact section with email, phone, LinkedIn, and a validated contact form.
- Scroll-based reveal animations.
- Automatically updated copyright year.
- Semantic HTML elements and descriptive image alt text.

---

## 📂 Project Structure

```text
rajvardhan-masterclass-portfolio/
│
├── index.html
├── README.md
│
└── images/
    ├── profile.jpg
    ├── project-1.jpg
    └── project-2.jpg
```

### File descriptions

- **`index.html`** — Contains the website structure, CSS styles, and JavaScript functionality.
- **`README.md`** — Provides project documentation and setup instructions.
- **`images/profile.jpg`** — Profile photograph displayed in the introduction section.
- **`images/project-1.jpg`** — Screenshot of the CodeVault project.
- **`images/project-2.jpg`** — Screenshot of the APEXA project.

**Important:** Create the `images` folder and add your actual image files using the exact filenames above. Keep the filenames and folder paths consistent with the references in `index.html`.

---

## 🖥️ Website Sections

### 1. Home

Introduces Rajvardhan Pradeep Vharambale as a Computer Science and Engineering student and aspiring software developer. Includes a profile image and links to the Projects and Contact sections.

### 2. About

Provides a short introduction, academic background, interests, and goals in software development.

### 3. Skills

Organizes skills into four categories:

- Programming: Python, Java, C++
- Frontend: HTML, CSS, React
- Tools and AI: Git, GitHub, VS Code, Prompt Engineering
- People skills: Leadership, Teamwork, Communication, Adaptability, Time Management

These skills reflect the information currently listed in the portfolio.

### 4. Projects

#### Project 01 — CodeVault

A cloud-based code execution platform that lets users write, compile, and run programs in multiple languages within isolated Docker containers.

**Technologies:** React, FastAPI, Python, PostgreSQL, Docker

**Focus:** Secure code execution and cloud containerization.

#### Project 02 — APEXA

A Python-based API analysis tool that evaluates API health, performance, security indicators, and response data quality. It generates actionable recommendations and detailed PDF reports.

**Technologies:** Python, Requests, CustomTkinter, SQLite, Matplotlib, ReportLab

**Focus:** API security analysis, performance monitoring, and automated reporting.

#### Project 03 — Java Text Editor

A desktop text editor built using Java Swing, focused on text editing and basic file operations.

**Technologies:** Java, Swing

**Focus:** Desktop application development and Java GUI fundamentals.

### 5. Education

Displays the following academic qualifications:

- **B.Tech — Computer Science and Engineering:** D. Y. Patil College of Engineering & Technology, Kolhapur (2024–2028); first-year CGPA: 8.89/10.
- **HSC:** Chate Junior College of Science, Kolhapur (2024); 82%.
- **SSC:** Private High School, Kolhapur (2022); 88%.

### 6. Experience — Learning Beyond the Classroom

Highlights involvement in college initiatives, placement coordination, and volunteering.

- **Placement Coordinator — Training and Placement (T/P) Cell:** Selected as a Placement Coordinator at D. Y. Patil College of Engineering & Technology, supporting placement-related coordination and communication between students and the cell.
- **Operations Team Member — Prarambh Development Cell:** Supported planning, coordination, and execution of technical and student-development initiatives.
- **Volunteer — SRIJAN DIPEX 2024:** Contributed to logistics, participant coordination, and event execution for a state-level engineering project exhibition.
- **NSS Volunteer:** Participated in community service and social-awareness activities.

### 7. Contact

Provides email, phone, and LinkedIn links, along with a contact form that prepares an email draft using the visitor's email application.

---

## 🚀 How to Run the Project

### Prerequisites

- A computer with a modern web browser.
- Visual Studio Code or another text editor.
- The project files and required images.

### Steps

1. Download or clone the project repository.
2. Open the project folder in Visual Studio Code.
3. Make sure `index.html` and the `images` folder are in the correct locations.
4. Add your profile photo as `images/profile.jpg`.
5. Add the CodeVault screenshot as `images/project-1.jpg`.
6. Add the APEXA screenshot as `images/project-2.jpg`.
7. Open `index.html` in your browser.

You can also use the **Live Server** extension in VS Code to preview the website while making changes.

No `npm install`, Python environment, database setup, or `requirements.txt` is needed to run the portfolio itself.

---

## 🧪 Testing and Validation

Test the following before publishing the website:

- [ ] Open `index.html` and confirm that the page loads.
- [ ] Confirm that the profile photo and both project screenshots display correctly.
- [ ] Click every navigation link and verify that it reaches the correct section.
- [ ] Test the mobile navigation menu.
- [ ] Check that all project descriptions and technology tags are readable.
- [ ] Verify email, phone, and LinkedIn links.
- [ ] Submit the contact form with valid details and confirm that an email draft opens.
- [ ] Test the layout on desktop, tablet, and mobile screen sizes.
- [ ] Check for broken images and browser-console errors.
- [ ] Validate the HTML using the W3C Markup Validation Service.

**HTML validator:** https://validator.w3.org/

The contact form uses a `mailto:` link. It opens a draft in a compatible email application; it does not send messages directly or store submissions on a server.

---

## 📚 HTML, CSS, and JavaScript Concepts Learned

### HTML5

- Standard HTML document structure.
- Headings, paragraphs, links, images, and lists.
- Semantic elements such as `header`, `nav`, `main`, `section`, and `footer`.
- Forms, labels, input types, and required-field validation.
- Image `src` and `alt` attributes.
- IDs for internal navigation between sections.

### CSS3

- CSS variables for reusable colors and values.
- Flexbox and CSS Grid for page layout.
- Responsive design using media queries.
- Background gradients, borders, shadows, and rounded corners.
- Hover transitions and scroll-reveal styling.
- Consistent spacing, typography, and color schemes.

### JavaScript

- Selecting and updating HTML elements using the DOM.
- Event listeners for button clicks and form submission.
- Toggling CSS classes for mobile navigation.
- Using `IntersectionObserver` for reveal animations.
- Reading and validating form values.
- Using `encodeURIComponent()` to prepare an email subject and body.
- Updating the copyright year dynamically.

---

## 🔐 Limitations

- The website is a static frontend project and does not use a backend or database.
- The contact form prepares an email draft; successful delivery depends on the visitor's email application and their action.
- Project screenshots must be supplied locally in the `images` folder.
- GitHub repository links or live demos should be added to project cards only when the corresponding links are available and verified.

---

## 🔮 Future Improvements

- Add verified GitHub repository and live-demo links for projects.
- Improve accessibility and keyboard navigation.
- Add a downloadable resume.
- Add a backend contact form with server-side validation.
- Add further projects, certifications, and technical achievements as they become available.
- Deploy the portfolio using GitHub Pages or another static hosting service.

---

## 👨‍💻 Author

**Rajvardhan Pradeep Vharambale**

Computer Science and Engineering Student  
D. Y. Patil College of Engineering & Technology, Kolhapur

- **Email:** rajvardhan2416@gmail.com
- **Phone:** +91 9322561422
- **LinkedIn:** https://www.linkedin.com/in/rajvardhan-pradeep-vharambale-9a6524417/

---

## 📄 License

This project was created for personal portfolio and learning purposes. Contact the author before reusing personal photographs or other personal content.
