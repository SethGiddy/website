# My IT Administrator CV Website

Just a personal portfolio site hosted on GitHub Pages. Push to master and it automatically goes live.

## What's Inside

My CV website with sections for experience, skills, projects, and education. Built with plain HTML and CSS, hosted via GitHub Actions deployment.

## Main Features

- Clean, responsive design that works on any device
- Auto-deploys to GitHub Pages whenever I push changes
- Works on all the usual browsers
- Easy to update and customize

## What Each Section Contains

- **Professional Summary** - Quick overview of what I do
- **Technical Skills** - Languages, tools, and platforms I work with
- **Projects** - Stuff I've built and worked on
- **Experience** - Previous roles and what I did there
- **Education & Certifications** - Degrees and certs I'm pursuing
- **Interests** - What I'm interested in tech-wise

## Getting It Live

### Auto Deploy

Just push to `master` and it deploys automatically through GitHub Actions (`.github/workflows/deploy.yml`).

### Manual Deploy

If you need to trigger a deployment manually:

1. Click the **Actions** tab
2. Find the **Deploy to GitHub Pages** workflow
3. Hit **Run workflow** on the master branch

## Viewing the Site

Once it's deployed, you'll find it at:

```text
https://[your-github-username].github.io/website/
```

## Updating Your Info

1. Open `index.html` and add your actual details
2. Update the name, email, phone, location in the header section
3. Fill in your real experience, projects, and skills
4. Commit and push - it'll redeploy in a few seconds

## GitHub Pages Setup

To get GitHub Pages working:

1. Go to **Settings** → **Pages**
2. Make sure **Source** is set to **GitHub Actions**

That's it. The GitHub Actions workflow handles the rest.

## Project Layout

```tree
.
├── index.html                    # The actual CV page
├── .github/
│   └── workflows/
│       └── deploy.yml            # Auto-deploy config
├── README.md                     # This file
└── .git/                         # Git stuff
```

## Browser Compatibility

Works fine on Chrome, Firefox, Safari, Edge - basically any modern browser.

## Using This Repo

It's yours to use and tweak however you want. Customize the styling, add new sections, whatever works for you.

## Quick Checklist

- [ ] Add your actual name and contact info
- [ ] Update with your real experience and projects
- [ ] Test a deployment by pushing a small change
- [ ] Share the link with people who might care
- [ ] Add a custom domain if you want (optional)

---

That's it! Good to go.

