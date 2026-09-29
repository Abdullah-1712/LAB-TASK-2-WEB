# HTML Lab Task 02

A Web Development lab project with **8 HTML5 & CSS pages**, all linked from one home page (`index.html`).

**Live demo:** https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

> Replace `YOUR-USERNAME` and `YOUR-REPO-NAME` with your GitHub username and repository name.

**Student:** Muhammad Abdullah 
**Course:** Web Technologies  
**Technology:** HTML5 & CSS

---

## Pages

| # | Question | File |
|---|----------|------|
| 1 | Job Application Portal | [`JOB.html`](JOB.html) |
| 2 | Online Event Registration | [`EVENT.html`](EVENT.html) |
| 3 | Digital Media Creator Showcase (video, audio, map) | [`DigitalMedia.html`](DigitalMedia.html) |
| 4 | Semantic Tech Blog | [`TechBlog.html`](TechBlog.html) |
| 5 | Educational Portal Dashboard (map, form) | [`Educational.html`](Educational.html) |
| 6 | Online Book Store | [`BookStore.html`](BookStore.html) |
| 7 | CS Student Portfolio | [`Portfolio.html`](Portfolio.html) |
| 8 | Responsive E-Commerce Product Website | [`Ecommerce.html`](Ecommerce.html) |

## Project structure

```
/
├── index.html          <- home page, links to all 8 questions
├── README.md
├── JOB.html            Q1
├── EVENT.html          Q2
├── DigitalMedia.html   Q3
├── TechBlog.html       Q4  (uses style.css)
├── Educational.html    Q5
├── BookStore.html      Q6
├── Portfolio.html      Q7
├── Ecommerce.html      Q8
├── style.css
└── *.svg               images used by the pages
```

All files sit in the same folder, so every link is a simple relative link and works both locally and online.

## Run locally

1. Download or clone the repository.
2. Double-click `index.html` to open it in your browser.
3. Use the menu or the list to open each question.

## Publish with GitHub Pages

1. Create a new repository on GitHub (for example `html-lab-task-02`).
2. Upload **the files themselves** (not a zip and not a parent folder) so that `index.html` is at the top level of the repository.
3. Go to **Settings -> Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
6. Wait about a minute. Your live link will be:
   `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Notes

- File names are case-sensitive on GitHub Pages: keep them exactly as written above (for example `JOB.html`, not `job.html`).
- Q3 and Q5 load a video, audio and maps from the internet, and Q6 to Q8 load Google Fonts, so those parts need an internet connection to show up.
