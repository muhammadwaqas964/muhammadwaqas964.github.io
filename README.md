# Muhammad Waqas — DevOps Portfolio Website

Source code for my personal DevOps portfolio, live on GitHub Pages.

**Live site:** https://muhammadwaqas964.github.io

## About Me

DevOps Engineer with 2+ years of production experience across Azure, AWS, and GCP: zero-downtime cloud migrations, CI/CD pipeline automation with security gates, GitOps on production Kubernetes, and infrastructure as code with Terraform and Ansible.

- **LinkedIn:** https://www.linkedin.com/in/muhammad-waqas366
- **Email:** waqaskhalid964@gmail.com

## About This Site

A clean, responsive single-page portfolio built with plain HTML and Tailwind CSS (CDN). No build step, no dependencies — clone and open `index.html`.

**Sections:** professional summary, work experience, featured projects, technical skills, and certifications. Dark theme, fully responsive, sticky navigation.

## Use This as Your Own Template

Feel free to fork this and make it yours.

### 1. Get the code

Fork this repository, or clone it:

```bash
git clone https://github.com/muhammadwaqas964/muhammadwaqas964.github.io.git
```

### 2. Customize `index.html`

- **Header & contact:** update the profile image `src`, name (`<h1>`), title (`<h2>`), phone, and the `href` links for email, LinkedIn, and GitHub in the `<header>` section
- **Summary:** edit the paragraph inside the section with `id="summary"`
- **Experience:** each role is a bordered `<div>` inside the section with `id="experience"` — edit the title (`<h4>`), dates (`<p class="text-sm">`), and description; duplicate a block to add roles
- **Projects:** each project is a `<div class="project-card">` inside the section with `id="projects"` — edit the image `src`, title (`<h4>`), and description (`<p>`); duplicate a card block to add more
- **Skills:** edit the `<li>` tags inside each `<div class="skill-category">` in the section with `id="skills"`
- **Certifications:** update the certification block at the end of the skills section

### 3. Replace images

Put your own profile photo and project images in the `Images/` folder and update the matching `src` paths in `index.html`.

### 4. Deploy on GitHub Pages

- **Forked?** Rename the repo to `your-username.github.io` — GitHub deploys it automatically as your main site.
- **Different repo name?** Go to **Settings → Pages → Build and deployment**, set Source to **Deploy from a branch**, select `main` and `/ (root)`, and save. The site goes live at `https://your-username.github.io/repo-name/` within minutes.