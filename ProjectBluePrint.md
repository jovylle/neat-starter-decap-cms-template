# ProjectBluePrint.md

## Project Overview
This project is a static site built using Eleventy, styled with Tailwind CSS, and includes a content management system using Netlify CMS. The site focuses on outdoor and sustainability themes.

## Key Technologies
- **Static Site Generator**: Eleventy
- **CMS**: Netlify CMS
- **Styling Framework**: Tailwind CSS
- **JavaScript Framework**: Alpine.js

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/jovylle/neat-starter-decap-cms-template.git
```

### 2. Navigate to the Directory
```bash
cd neat-starter-decap-cms-template
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Build the Project
This step is only required the very first time.
```bash
npm run build
```

### 5. Run Eleventy
```bash
npm run start
```

### 6. Run Netlify CMS Proxy Server
```bash
npx netlify-cms-proxy-server
```

## Project Structure
```
project-root/
│
├── .eleventyignore            # Files excluded from building
├── package.json               # Project dependencies and scripts
├── README.md                  # Project overview and setup instructions
└── src/                       # Source files
    ├── _data/                 # Data files
    ├── _includes/             # HTML snippets and layouts
    ├── admin/                 # Netlify CMS configuration
    ├── posts/                 # Blog posts
    ├── static/                # Static assets (CSS, JavaScript, images)
    └── index.html             # Main entry point for the site
```

## Important Files
- **`.eleventyignore`**: Specifies files and directories that Eleventy should ignore.
- **`package.json`**: Contains scripts for building and running the site, as well as dependencies required for development.
- **`src/_includes/default.html`**: The main layout file used across various pages.
- **`src/_includes/partials/navbar.html`**: Contains the navigation bar structure for the site.
- **`src/_includes/partials/footer.html`**: Contains the footer structure for the site.
- **`src/admin/index.html`**: The entry point for Netlify CMS.
- **`src/posts/*.md`**: Markdown files for blog content.

## Notes
This blueprint serves as a comprehensive reference for setting up and understanding the project. For further details on specific technologies (like Eleventy or Netlify CMS), refer to their official documentation.