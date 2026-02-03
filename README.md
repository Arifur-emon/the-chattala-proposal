
# The Chattala — SE Project Proposal

This repository contains the Software Engineering project proposal for **The Chattala** — a centralized hub for community Q&A and digital commerce in Chattogram.

## Structure

```
the-chattala-proposal/
├─ proposal.tex                # LaTeX source (compile to PDF)
├─ docs/
│  └─ The_Chattala_SE_Project_Proposal_Detailed.docx
├─ .github/workflows/latex.yml # GitHub Actions to build PDF from LaTeX
├─ .gitignore                  # Ignore LaTeX build artifacts
└─ LICENSE                     # MIT License
```

## How to build the PDF locally (XeLaTeX recommended)

```bash
# On your machine
xelatex proposal.tex
# or
pdflatex proposal.tex
```

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit: Chattala SE proposal"
# If your default branch is 'master', rename to 'main'
git branch -M main
# Replace <YOUR-USERNAME> with your GitHub username
# Create an empty repo on GitHub first, then:
git remote add origin https://github.com/<YOUR-USERNAME>/the-chattala-proposal.git
git push -u origin main
```

## (Optional) GitHub Pages to host the PDF
- Enable **Settings → Pages** and select branch `main` and root.
- After Actions build, upload the generated `proposal.pdf` to the repo (or commit it), then it will be available via a public URL.

---

© ubuntu — MIT Licensed.
