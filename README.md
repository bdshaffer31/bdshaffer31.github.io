# Minimal Academic Website Template (Multi-Page Version)

This is a **multi-page extension** (by me [Ahmad D. Suleiman](https://ahmadfantastic.github.io)) original [Minimal Academic Website Template](https://cs.stanford.edu/~yuhuiz/) created by [Yuhui Zhang](https://cs.stanford.edu/~yuhuiz/).  
The original design and source code are licensed under the MIT License.

## What’s New in This Version

- Multi-page layout with navigation bar
- Improved organization for sections (About, Research, Publications, News, etc.)
- Easier scalability for larger websites
- Preserves the minimalist, academic-focused design of the original


![Demo](images/demo.gif)

## Original Features

- Minimalist, academic-focused design
- Responsive layout
- Easy to customize
- SEO-friendly meta tags
- Publication showcase support

## Quick Start

0. Clone this repository and `cd` into the directory
1. Run `python -m http.server` and visit `http://localhost:8000`
2. Replace placeholders in HTML files marked like `[Name]`, `[University]`, `[Research Topic]`, `[YYYY]`, etc.
3. Update meta tags in each page head (description, keywords, author, title, og:url).
4. Add `CV.pdf` to the repo root if you want the "CV" nav item to download.
3. Update profile photo in `images/profile.jpeg`
4. Modify `publications.json` for your papers
5. Customize sections as needed (About, Research, News, etc.)

## File Structure

```
.
├── index.html          # Main webpage
├── styles.css          # CSS styling
├── scripts.js          # JavaScript for dynamic content
├── publications.json   # Publication data
└── images/            # Image assets
    └── profile.jpg
```

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.  
The original template was created by [Yuhui Zhang](https://cs.stanford.edu/~yuhuiz/).
