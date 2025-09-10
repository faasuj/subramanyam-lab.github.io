# Systems Optimization Laboratory @ Penn State — Website Contributor Guide

Welcome to the Systems Optimization Lab website repository!  
This README explains how to update your personal profile, add news items, and manage publications. Follow these instructions to keep our site accurate and up to date.

---

## 1. Editing Your Profile

Each lab member has a profile file in `_pages/about/`.

**To update your profile:**

1. Locate your profile file (e.g., `_pages/about/eduardo.md`).
2. Edit the file using Markdown. Update your name, research topic, email, and relevant links.

**Profile Template:**

```markdown
## Your Name

_Joined group in [Semester Year]_

Research topic: [Your research topic]

Email: [mailto:your.email@domain.edu](mailto:your.email@domain.edu)
Links: [LinkedIn](https://linkedin.com/in/yourprofile)
```

3. Save and commit your changes. Use a descriptive commit message (e.g., `Update profile for Eduardo Lopez Ledezma`).

---

## 2. Adding or Editing News Items

News items are stored in the `_news/` directory as Markdown files.

**To add a news item:**

1. Create a new file in `_news/` named `YYYY-MM-DD-title.md`.
2. Use this template:

```markdown
---
title: "Short News Title"
date: YYYY-MM-DD
author: Your Name
---

Brief description of the news item.
```

**To edit an existing news item:**

- Open the relevant file in `_news/` and make your changes.

---

## 3. Adding or Editing Publications

Publications are listed in the `_publications/` directory.

**To add a publication:**

1. Create a new file in `_publications/` named `YYYY-title.md`.
2. Use this template:

```markdown
---
title: "Publication Title"
authors: Author1, Author2, Author3
journal: Journal Name
year: YYYY
doi: https://doi.org/xxxx
---

Short summary or abstract of the publication.
```

**To edit a publication:**

- Open the relevant file in `_publications/` and update details as needed.

---

## 4. Submitting Your Changes

After editing, commit your changes and push to GitHub.  
If you do not have write access, submit a Pull Request for review.

---

## Need Help?

Questions or issues? Contact the repository maintainer or open a GitHub issue.

---

Happy contributing!
