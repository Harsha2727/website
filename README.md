# 🌐 Personal Portfolio Website

A responsive personal portfolio website built using HTML, CSS, and GitHub Pages.

---

## 🔧 Tools Used

| Tool                  | Purpose                                           |
|-----------------------|---------------------------------------------------|
| VS Code               | Code editor to build HTML/CSS/JS                  |
| HTML/CSS/JavaScript   | For building and styling the website              |
| Git                   | Version control system                            |
| GitHub                | Remote repository for storing code & deployment   |
| GitHub Pages          | Free hosting for the website                      |
| Google Fonts          | Typography improvement                            |
| Font Awesome          | Icons for social media & sections                 |
| Chrome DevTools       | Testing and debugging the layout                  |

---

## 🚀 Step 1: Setting Up the Project

- Created a project folder called `personal-website` on my local machine.
- Inside the folder, I created the following file:
  - `Personal-Portfolio.html` — the main HTML file.

---

## ✨ Step 2: Designing the Website

### Sections:
1. **Header** – Includes my name and a navigation bar.
2. **About Me** – A short paragraph introducing myself.
3. **Education** – My academic background.
4. **Skills** – A list of technical and soft skills.
5. **Projects** – Cards or sections showing my past work with descriptions and GitHub links.
6. **Contact** – Email and social media links.

### 🎨 Design Choices:
- **Color Theme**: Minimalist color palette (white background with blue accents).
- **Font**: Google Font 'Poppins' for a clean, modern look.
- **Responsiveness**: Media queries used to ensure mobile-friendliness.
- **Icons**: Font Awesome for visual elements.

---

## 🛠 Step 3: Initializing Git and Version Control

1. Opened terminal in the project folder.
2. Ran the following commands:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    git branch -M main
    ```
3. Created a GitHub repository called `website`.
4. Connected local repo to GitHub:
    ```bash
    git remote add origin https://github.com/Harsha2727/website.git
    git push -u origin main
    ```

---

## 🔁 Step 4: Making Updates and Tracking with Git

- After every update to HTML/CSS, I ran:
    ```bash
    git add .
    git commit -m "Updated contact section"
    git push
    ```
- Helped maintain version history and rollback changes if needed.

---

## 🌐 Step 5: Deploying to GitHub Pages

1. Went to the repository on GitHub.
2. Navigated to **Settings > Pages**.
3. Selected the `main` branch and clicked **Save**.
4. GitHub generated a live link to access the website.
5. Tested the link to ensure the website loaded properly.

---

## 🧩 Challenges Faced

| Challenge                          | Solution                                                                 |
|-----------------------------------|--------------------------------------------------------------------------|
| Website not centered on mobile    | Used CSS Flexbox and media queries                                       |
| `src refspec main does not match` | Performed a first commit and renamed the branch to `main`               |
| Remote origin already exists      | Removed it with `git remote remove origin` and added again              |
| Font not loading                  | Correctly added Google Fonts `<link>` tag in the HTML `<head>`          |
| Page not updating after push      | Cleared browser cache & confirmed latest push to GitHub was successful  |

---

## 📌 Live Website

🚀 [Visit My Portfolio]()

---

