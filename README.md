# IT Administrator CV Website

A professional CV website hosted on GitHub Pages using automated GitHub Actions deployment.

## Overview

This repository contains a CV/resume website showcasing IT Administration experience, technical skills, and projects. The site is automatically deployed to GitHub Pages on every push to the `master` branch.

## Features

- 📄 Clean and professional CV layout
- 🚀 Automated deployment via GitHub Actions
- 🌐 Hosted on GitHub Pages
- 📱 Responsive HTML design

## Website Sections

- **Professional Summary** - Overview of skills and experience
- **Technical Skills** - Key competencies (Linux, Git, Azure, Docker, Bash)
- **Projects** - Notable projects and implementations
- **Experience** - Previous IT roles and responsibilities
- **Education & Certifications** - Credentials and ongoing learning
- **Interests** - Professional interests and areas of focus

## Deployment

### Automatic Deployment

The site is automatically deployed to GitHub Pages whenever you push changes to the `master` branch. This is handled by the GitHub Actions workflow defined in `.github/workflows/deploy.yml`.

### Manual Deployment

You can also trigger a manual deployment:

1. Go to the **Actions** tab in your GitHub repository
2. Select **Deploy to GitHub Pages** workflow
3. Click **Run workflow** on the `master` branch

## Viewing Your Website

Once deployed, your website will be available at:

```
https://[your-github-username].github.io/website/
```

Replace `[your-github-username]` with your actual GitHub username.

## Making Changes

1. Edit the `index.html` file with your information
2. Update your name, email, phone, and location in the header
3. Modify the content sections with your actual experience
4. Commit and push your changes to `master`
5. The site will automatically redeploy within seconds

## Repository Settings

Ensure your GitHub repository has GitHub Pages enabled:

1. Go to **Settings** → **Pages**
2. Verify that **Source** is set to **Deploy from a branch**
3. Select the **branch** and **folder** (should be automatic with this workflow)

The workflow uses **GitHub Actions** to build and deploy, so no manual configuration is needed beyond pushing changes.

## Project Structure

```
.
├── index.html                    # Main CV webpage
├── .github/
│   └── workflows/
│       └── deploy.yml            # GitHub Actions deployment workflow
├── README.md                     # This file
└── .git/                         # Git repository data
```

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge).

## License

This repository is yours to use and modify. Feel free to customize it for your needs.

## Next Steps

- [ ] Update your personal information in `index.html`
- [ ] Add your actual experience, projects, and skills
- [ ] Test the deployment by pushing changes
- [ ] Share your portfolio URL with employers and contacts
- [ ] Consider adding CSS enhancements or a custom domain

---

**Happy deploying!** 🎉
