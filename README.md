# Ibtissame Abdoussi – Portfolio

Personal portfolio of Ibtissame Abdoussi, 5th-year engineering student at ENSA Oujda (GSEIR), specialized in embedded systems, IoT and robotics. I am currently looking for a 5-month end-of-studies internship (PFE).

## Contents

- **Professional experience:** condition-based maintenance and industrial IoT internship at OCP Group
- **Technical skills:** embedded systems, electronic design and CAD, robotics and control, programming, digital design, industrial automation, data processing
- **Projects:** eight academic and extracurricular projects, filterable by category (Robotics & ROS, IoT & Embedded, Control & AI), each with a photo album
- **Education, activities, languages and interests**
- **Contact details**

## Tech stack

Plain HTML, CSS and JavaScript in a single file, with no framework and no build step. Fonts (Syne, IBM Plex Mono, DM Sans) are loaded from Google Fonts.

## Project structure

```
.
├── index.html
├── README.md
└── images/
    ├── me.jpg
    ├── WhatsApp Image 2026-04-26 at 23.10.23.jpeg
    └── WhatsApp Image 2026-04-26 at 23.10.20.jpeg
```

All photos live in the `images/` folder. The file names must match the ones used in `index.html`, otherwise the photos will not display.

## Run locally

1. Download or clone the repository.
2. Open `index.html` in your browser.

## Edit the content

- **Skills and projects** are defined in the `SKILLS` and `PROJECTS` lists at the bottom of `index.html`. Edit the text there, and the page updates automatically.
- **Add a project** by copying an existing entry in `PROJECTS` and changing its `id`, `cat`, `title`, `desc`, `tags` and `slides`.
- **Project photos:** put the image in the `images/` folder, then add a fourth value to a slide with just the file name, for example `['📷','Prototype','','my-photo.jpg']`. The `images/` path is added automatically (it is set once by `IMG_DIR` in the script). Without the fourth value, the slide shows an upload placeholder.
- **Profile photo:** replace `images/me.jpg` with your own picture, keeping the same name.
- **Filter categories** are `robotics`, `iot` and `control`. Set them in the `cat` field of each project, separated by spaces.

> Photos added through the on-page upload placeholders only exist in the visitor's browser. They disappear on refresh and are not visible to other visitors. Add the image files to the repository and reference them as described above to keep them.

## Deploy

### GitHub Pages

1. Push the files to a GitHub repository, including the `images/` folder.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the main branch and the root folder, then save.
4. The site is live after about a minute. After any change, commit and push to update it:

```
git add .
git commit -m "Update portfolio"
git push
```

The page also works on Netlify, Vercel or any static host. Upload the folder as it is.

## Contact

- Email: ibtissam.abdoussi.23@ump.ac.ma
- Phone: 0664520040
- Location: Oujda, Morocco

© 2026 Ibtissame Abdoussi
