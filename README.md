Muhammad Waqas - DevOps Portfolio Website

This repository contains the source code for my personal DevOps portfolio website, hosted live on GitHub Pages.

Live Demo: https://muhammadwaqas964.github.io

About This Portfolio

This is a clean, modern, and fully responsive single-page portfolio designed to showcase my skills and projects as a DevOps Engineer. It is built with plain HTML and styled using Tailwind CSS.

Features

Sleek Dark Mode: A professional, developer-friendly dark theme.

Fully Responsive: Looks great on all devices, from mobile phones to desktops.

Sticky Navigation: An easy-to-use navigation bar that sticks to the top.

Dynamic Content: Project and skill sections are easy to update.

Zero Dependencies: Runs on pure HTML and a Tailwind CSS CDN link, making it lightweight and fast.

How to Use This as Your Own Template

You can easily use this repository as a template to build your own portfolio website.

Step 1: Get the Code

You have two options:

Fork this Repository: Click the "Fork" button at the top-right of this page to create a copy of this repository on your own GitHub account.

Clone this Repository: If you prefer to work locally first, clone the repository to your machine:

git clone [https://github.com/muhammadwaqas964/muhammadwaqas964.github.io.git](https://github.com/muhammadwaqas964/muhammadwaqas964.github.io.git)


Step 2: Customize Your Content

Open the index.html file in your favorite code editor and begin customizing the content.

1. Header & Contact Info

Find the <header> section (around line 43) to change:

Profile Picture: Update the src attribute for the <img> tag (around line 46) to point to your photo (e.g., src="Images/your-photo.jpg").

Name & Title: Edit the <h1> (Name) and <h2> (Title) tags.

Contact Details: Update the phone number, location, and the href links for your Gmail, LinkedIn, and GitHub profiles.

2. Professional Summary

Find the section with id="summary" (around line 73) and edit the paragraph (<p>) text to add your own professional summary.

3. Featured Projects

Find the section with id="projects" (around line 83). Each project is a div with the class .project-card.
To add, edit, or remove projects:

Project Image: Change the src in the <img> tag.

Project Title: Edit the text inside the <h4> tag.

Project Description: Edit the text inside the <p> tag.

You can copy and paste the entire .project-card block to add more projects.

4. Technical Skills

Find the section with id="skills" (around line 140). Each skill category is a div with the class .skill-category.

Category Title: Edit the <h4> tag (e.g., "Cloud Computing").

Skill Tags: Add, remove, or edit the <li> items in the list (<ul>) to match your skills.

5. Certifications

Find the div at the end of the skills section (around line 184) to update your certification details.

Step 3: Replace Images

Go into the Images/ folder.

Add your own profile picture and project images.

Make sure you update the src="..." paths in the index.html file (as described in Step 2) to match the new filenames of your images.

Step 4: Deploy Your Site on GitHub Pages

If you forked the repository, rename it to your-username.github.io (replacing your-username with your GitHub username). GitHub will automatically build and deploy it as your main portfolio site.

If you named the repository something else (e.g., my-portfolio):

Go to your repository's Settings tab.

In the side menu, click on Pages.

Under "Build and deployment," set the Source to Deploy from a branch.

Select the main (or master) branch and the / (root) folder.

Click Save.

Your new portfolio website will be live at https://your-username.github.io/my-portfolio/ in a few minutes.

License

This project is open-sourced under the MIT License.
