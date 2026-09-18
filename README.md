Các Loại Dữ Liệu Trong NCKH | Data Types in Scientific Research
Interactive bilingual (Vietnamese / English) web tool for teaching data types in scientific research (NCKH):
Nominal (Định danh)
Ordinal (Thứ bậc)
Continuous (Liên tục)
Students progress through 5 guided steps:
Warm-up – Learn definitions + classify cards + comparison table
Design – Design a short survey (Gender + Ordinal + Continuous questions)
Collection – Enter / auto-fill sample data + export CSV
Analysis – Step-by-step JASP workflow for each data type
Summary – Build a mini scientific report (tables, charts upload, conclusions)
Live Demo (GitHub Pages)
After you enable GitHub Pages (see below):
```
https://<your-username>.github.io/<repo-name>/
```
Features
Fully bilingual (VI ↔ EN toggle)
Card classification game with instant feedback
Editable survey + data table (10 respondents)
CSV export (UTF-8 with BOM for Excel)
Guided JASP analysis instructions
Report builder with image upload for charts
Responsive design (desktop + tablet)
Tech Stack
React 18 (CDN)
Babel Standalone (in-browser JSX)
Tailwind CSS (CDN)
Lucide Icons
Pure static HTML – no build step required
How to run locally
Clone the repository:
```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
Open `index.html` in any modern browser  
(or use a simple local server):
```bash
   # Python 3
   python -m http.server 8000
   # then visit http://localhost:8000
   ```
Deploy to GitHub Pages
Create a new repository on GitHub (e.g. `data-types-nckh`).
Push this project:
```bash
   git init
   git add .
   git commit -m "Initial commit: bilingual data types learning tool"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
On GitHub → Settings → Pages:
Source: Deploy from a branch
Branch: `main` / folder: `/ (root)`
Save
Wait 1–2 minutes. Your site will be live at:
```
   https://<your-username>.github.io/<repo-name>/
   ```
Project structure
```
data-types-nckh/
├── index.html      # Complete single-file React application
├── README.md       # This file
└── .gitignore
```
License
MIT License – feel free to use, modify, and share for educational purposes.
---
Tác giả / Author: Educational tool for teaching scientific research methodology (NCKH) in secondary/high school.
