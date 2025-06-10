# 💼 Harini Sree's Portfolio

Welcome to my personal portfolio website! This project showcases my skills, experiences, and projects in a clean and responsive format using basic web technologies.

🔗 **Live Website**: [https://harinisree1212.github.io/portfolio/](https://harinisree1212.github.io/portfolio/)

---

## 📌 Overview

This website is a fully static, multi-page portfolio built using HTML, CSS, and JavaScript. It was designed and deployed with the goal of representing my professional profile and making it easier for recruiters and collaborators to view my work.

---

## 🧠 My Git & GitHub Understanding

Here’s what I learned and used while building and deploying this project:

### 🔁 Git Concepts

| Command | Purpose |
|--------|-------------|
| `git init` | Initialized the local repository |
| `git status` | Checked file status before commits |
| `git add .` | Staged all changes |
| `git commit -m "message"` | Committed changes with messages |
| `git remote add origin <url>` | Linked local repo to GitHub |
| `git push -u origin main` | Pushed code to GitHub |
| `git pull origin main --rebase` | Pulled changes to resolve remote conflicts |

### 🌐 GitHub Pages Deployment

- Hosted using **GitHub Pages**
- Enabled GitHub Pages from repository settings and selected `main` branch as the source

---

## 📁 Folder Structure

```plaintext
portfolio/
├── index.html         # Home page
├── about.html         # About Me section
├── contact.html       # Contact form
├── style.css          # Styling for all pages
├── script.js          # JS for interactivity
└── assets/            # Images, icons, logos
```

---

## 🧩 Component & Code Explanation

### 🔹 `index.html`

- **Header/Nav Bar**: Navigation to different sections
- **Hero Section**: Profile image, title, and bio
- **Skills/Projects**: Displays cards with skill names or sample projects
- **Footer**: Contact/social info

```html
<header>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>
```

---

### 🔹 `about.html`

- Displays academic qualifications, certifications, and strengths

```html
<section id="education">
  <h2>Education</h2>
  <p>B.Tech in Information Technology, [University Name]</p>
</section>
```

---

### 🔹 `contact.html`

- Contains an HTML5 contact form

```html
<form action="#" method="post">
  <input type="text" name="name" required placeholder="Your Name">
  <input type="email" name="email" required placeholder="Your Email">
  <textarea name="message" required placeholder="Your Message"></textarea>
  <button type="submit">Send</button>
</form>
```

---

### 🔹 `style.css`

- Used for custom styling

```css
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fff;
}
nav a:hover {
  color: #ff6600;
}
@media screen and (max-width: 768px) {
  nav {
    flex-direction: column;
  }
}
```

---

### 🔹 `script.js`

- Adds simple interactivity (if used)

```javascript
document.querySelector("form").addEventListener("submit", function (e) {
  alert("Thank you for contacting me!");
});
```

---

## 🛠️ Technologies Used

- **HTML5** – Markup language for structure
- **CSS3** – Styling and layout
- **JavaScript** – Basic functionality
- **Git & GitHub** – Version control
- **GitHub Pages** – Free static site hosting

---

---

## 🧠 My Understanding of Git & GitHub

While building this project, I gained a solid understanding of **Git** and **GitHub** — essential tools for version control and collaboration.

### ✅ What I've Learned:

- **Version Control Basics**:
  - Git helps track changes in my project, so I can revert back or compare versions anytime.
  - I can manage and maintain clean project histories using commits.

- **Staging & Committing**:
  - Used `git add` to stage changes and `git commit` to save snapshots of my project with clear messages.

- **Repository Setup**:
  - Initialized a local Git repository using `git init`.
  - Created and connected a remote repository on GitHub using:
    ```bash
    git remote add origin <repo-url>
    git push -u origin main
    ```

- **Branching & Merging (basic intro)**:
  - Learned the concept of branches to work on features independently.
  - Got introduced to merge conflicts and how to resolve them.

- **Error Handling**:
  - Faced push errors like:
    ```
    ! [rejected] main -> main (fetch first)
    ```
    - Learned to fix them using:
      ```bash
      git pull origin main --rebase
      git push origin main
      ```

- **Deployment**:
  - Understood how to deploy websites using **GitHub Pages** by selecting the `main` branch and root directory.

### 🛠 Commands I Frequently Used:

```bash
git init                    # Initialize repo
git status                 # Check current changes
git add .                  # Stage all changes
git commit -m "Message"    # Commit with a message
git remote add origin URL  # Link to GitHub
git push -u origin main    # Push changes
git pull origin main       # Sync changes from remote
```

This project gave me hands-on experience with Git and taught me the importance of version control in real-world projects.

---

## 🚀 Future Enhancements

- Add animations using AOS.js or CSS transitions
- Add project cards with GitHub links
- Connect contact form to Formspree or EmailJS
- Add dark/light theme toggle

---

## 📬 Contact

If you'd like to connect or collaborate:

- Email: [your email]
- LinkedIn: [your LinkedIn profile link]

---

> Created with 💖 by Harini Sree | Hosted on GitHub Pages
