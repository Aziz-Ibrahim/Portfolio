# Student Web Developer Portfolio
This is a personal portfolio website for showcasing the work and skills of a student web developer. The website includes sections for an About Me profile, Projects, Skills, Contact form, and links to GitHub and LinkedIn profiles. Visitors can also download the developer's resume directly from the site.

## Table of Contents
Features
Technologies Used
Setup
File Structure
Customization
License

## Features
Responsive Design: The portfolio is designed to be responsive, working well on both desktop and mobile devices.
Profile Section: Includes a photo, name, short bio, and a button to download the resume.
Projects Section: Showcases a few projects with descriptions of technologies used.
Skills Section: Lists important technical skills such as HTML, CSS, JavaScript, and more.
Contact Form: Allows visitors to send messages via email.
Footer with Social Links: Links to GitHub and LinkedIn profiles.

## Technologies Used
HTML5: For structuring the webpage content.
CSS3: For styling the webpage, including responsiveness.
JavaScript: Basic form submission functionality.
Font Awesome: For displaying GitHub and LinkedIn icons in the footer.
Sidebar nav is inspired by the work of alphardex on Code Pen [https://codepen.io/alphardex]

## Setup
To run this website locally on your computer:

### 1-Clone the repository:

git clone https://github.com/yourusername/portfolio-website.git

### 2-Navigate to the project directory:

cd portfolio-website

### 3-Open the index.html file in your browser:
 You can simply open the file directly in a browser or use a live server for better development experience (e.g., using VS Code's Live Server extension).

## File Structure
The project consists of the following files:

portfolio-website/
│
├── index.html          # Main HTML file that contains the structure of the portfolio
├── styles.css          # Main CSS file for styling the website
├── resume.pdf          # The resume that users can download (replace with your own)
├── profile.jpg         # Profile image used in the About section
├── README.md           # This README file
└── /assets             # (Optional) Directory for additional assets like images, icons

## Customization
Feel free to customize this portfolio template to fit your needs:

### Profile Information: 
In the index.html file, update the name, profile picture, bio, and the link to your resume.

html
<img src="./assets/images/profile.jpg" alt="Profile Picture">
<h1>Aziz Ibrahim</h1>
<p>Web Developer & Computer Science Student</p>
<a href="resume.pdf" download="my_Resume.pdf" class="download-btn">Download Resume</a>

### Projects Section:
 Update the project titles, descriptions, and add more projects if needed.

<div class="project-card">
    <h3>Project 1</h3>
    <p>Description of the project goes here. You can describe what technologies you used, and what the project accomplished.</p>
</div>

### Skills Section: 
Add or remove skills as needed.

<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
    <!-- Add more skills here -->
</ul>

### Social Media Links: 
Update the links to your GitHub and LinkedIn profiles in the footer.


<a href="https://github.com/your-github-username" target="_blank">
    <i class="fab fa-github"></i>
</a>
<a href="https://www.linkedin.com/in/your-linkedin-profile" target="_blank">
    <i class="fab fa-linkedin"></i>
</a>

### Resume File: 
Replace the my_Resume.pdf file in the root directory with your actual resume.

## License
This project is open-source and free to use under the MIT License. Feel free to modify and customize it for your personal or professional use.