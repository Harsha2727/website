Step-by-Step Documentation: Personal Portfolio Website
________________________________________
🔧 Tools Used
Tool	Purpose
VS Code	Code editor to build HTML/CSS/JS
HTML/CSS/JavaScript	For building and styling the website
Git	Version control system
GitHub	Remote repository for storing code and deploying the website
GitHub Pages	Free hosting for the website
Google Fonts & Font Awesome	For better typography and icons
Chrome DevTools	To test and debug the layout
________________________________________
🚀 Step 1: Setting Up the Project
•	I created a project folder on my local machine called personal-website.
•	Inside the folder, I created the following files:
o	Personal-Portfolio.html — the main HTML file.
________________________________________
✨ Step 2: Designing the Website
I divided my website into the following sections:
1.	Header — includes my name and a navigation bar.
2.	About Me — a short paragraph introducing myself.
3.	Education — my academic background.
4.	Skills — a list of technical and soft skills.
5.	Projects — cards or sections showing my past work with descriptions and GitHub links.
6.	Contact — email and social media links.
🎨 Design Choices:
•	Color Theme: I chose a minimalist color palette (white background with blue accents) for clarity and professionalism.
•	Font: Used Google Fonts like Poppins for a clean modern look.
•	Responsiveness: I used media queries to make the layout mobile-friendly.
•	Icons: Used Font Awesome for social media and section icons.
________________________________________
🛠 Step 3: Initializing Git and Version Control
1.	Opened terminal in the project folder.
2.	Ran the following commands:
git init
git add .
git commit -m "Initial commit"
git branch -M main
3.	Created a new GitHub repository called website.
4.	Connected my local project to GitHub using:
git remote add origin https://github.com/Harsha2727/website.git
git push -u origin main
________________________________________
🔁 Step 4: Making Updates and Tracking with Git
•	Every time I updated the HTML/CSS, I committed and pushed the changes:
git add .
git commit -m "Updated contact section"
git push
•	This helped me maintain a history of all the changes and roll back if needed.
________________________________________
🌐 Step 5: Deploying to GitHub Pages
1.	Went to the repository on GitHub.
2.	Clicked on Settings > Pages.
3.	Selected the main branch and clicked Save.
4.	GitHub provided a live link:

5.	Tested the link to ensure everything loaded correctly.
________________________________________
🧩 Challenges Faced
Challenge	How I Solved It
Website not centered on mobile	Used CSS Flexbox and media queries
"src refspec main does not match any"	Realized I hadn't committed yet; fixed with a first commit and branch rename
Remote origin already exists	Removed it with git remote remove origin and added again
Font not loading	Added correct Google Fonts <link> in the HTML head
Page not updating after push	Cleared browser cache and confirmed changes were pushed properly
________________________________________

