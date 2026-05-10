# Ranjit Kumar Nayak — Portfolio

**Lead RPA & Agentic AI Architect · 13+ Years**

Live portfolio site for [ranjitnk.github.io](https://ranjitnk.github.io)

---

## 🚀 Deploy to GitHub Pages (5 minutes)

### Step 1: Create the repo
1. Go to [github.com/new](https://github.com/new)
2. Name it exactly: `<your-github-username>.github.io`  
   *(e.g. `ranjitnk.github.io`)*
3. Set to **Public**
4. Don't initialize with README (you'll push this one)

### Step 2: Push this folder
```bash
cd ranjit-portfolio
git init
git add .
git commit -m "Initial portfolio launch"
git branch -M main
git remote add origin https://github.com/ranjitnk/ranjitnk.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from branch** → `main` → `/ (root)`
3. Save. Your site is live in ~60 seconds at `https://ranjitnk.github.io`

---

## 📁 File Structure

```
ranjit-portfolio/
├── index.html          ← Main portfolio (single-file, no build needed)
├── resume.pdf          ← ADD YOUR RESUME HERE (rename to resume.pdf)
├── og-preview.png      ← ADD social preview image (1200×630px)
├── README.md           ← This file
└── .github/
    └── workflows/
        └── deploy.yml  ← Auto-deploy on push (optional CI/CD)
```

---

## ✏️ Personalisation Checklist

### Must-update before publishing:
- [ ] Replace `ranjitnk` with your actual GitHub username in all URLs
- [ ] Update `canonical` URL in `<head>` SEO section
- [ ] Add `resume.pdf` file to the folder
- [ ] Add `og-preview.png` (1200×630px) for social previews
- [ ] Update `og:image` URL to point to your actual hosted image
- [ ] Update `<link rel="canonical">` to your real URL

### High impact (do before sharing with recruiters):
- [ ] **Fill in real metrics** — search for `~40K`, `200+` etc. and update with actual numbers
- [ ] **Add real LLM names** — replace `GPT-4 / Local` with what you actually used (Ollama + Mistral? GPT-4o? Claude API?)
- [ ] **Verify credential links** — update the 3 "Verify Credential ↗" links in Certifications section
- [ ] **Availability date** — update "Available Q3 2025" in nav, hero, and contact sections
- [ ] **Add architecture diagrams** — export sanitised diagrams from draw.io / Lucidchart, place in `/diagrams/` folder, replace the inline ASCII diagrams

### Nice to have:
- [ ] Add a favicon: `<link rel="icon" href="favicon.ico" />`
- [ ] Add Google Analytics: `gtag.js` snippet before `</head>`
- [ ] Add Hotjar or Microsoft Clarity for visitor heatmaps
- [ ] Add a `sitemap.xml` for better Google indexing

---

## 🔍 SEO Keywords Targeted

This portfolio is optimised for the following recruiter search terms:

| Keyword | Placement |
|---|---|
| RPA Architect India | meta, schema, body |
| UiPath Certified | meta, hero, certifications |
| Agentic AI Lead | meta, hero, timeline |
| ABBYY Vantage | meta, stack, case studies |
| Automation Anywhere A360 | meta, stack |
| HIPAA Compliance Automation | meta, case study 03 |
| Oracle Fusion RPA | meta, case study 02 |
| LLM Integration RPA | meta, stack |
| FastAPI Python Automation | meta, stack, case study 01 |
| Enterprise Automation Bengaluru | meta, contact |

---

## 🏗 Architecture Diagram Instructions

Replace placeholder diagrams with real exports:

1. Use **draw.io** (free): [app.diagrams.net](https://app.diagrams.net)
2. Export as PNG or SVG at 2x resolution
3. Sanitise client names (use "Healthcare Client A" not real names)
4. Save to `/diagrams/arch-01-agentic.png` etc.
5. In `index.html`, replace the `<div class="arch-box">` blocks with:

```html
<img src="diagrams/arch-01-agentic.png" 
     alt="Agentic AI Extraction Engine Architecture" 
     class="w-full border border-border" />
```

---

## 📊 Metrics to Research Before Publishing

Pull these numbers from your actual project data:

| Metric | Where to Find It |
|---|---|
| Hours automated/month | UiPath Orchestrator analytics dashboard |
| Bot count | Orchestrator → Processes list |
| Error rate before/after | Process logs or project documentation |
| Invoice volume processed | Client reports or project metrics |
| Team size led | Your own memory / LinkedIn |
| Cost savings | Effort hours × resource rate calculation |

Even **estimated/directional** numbers ("reduced processing time by approximately 80%") are far better than no numbers. Talk to your former clients/managers to get sign-off on sharing ranges.

---

## 💡 Recruiter Attraction Tips

1. **LinkedIn canonical link**: In your LinkedIn "About" section, add `Portfolio: https://ranjitnk.github.io`
2. **Email signature**: Add portfolio URL to every email signature
3. **GitHub profile README**: Create `ranjitnk/ranjitnk` repo with a README that links here
4. **Medium / Dev.to article**: Write one article on "Building Agentic Routing with FastAPI + UiPath" and link back to portfolio
5. **UiPath Community**: Post in UiPath Forum linking to the Agentic Extractor case study

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| Pure HTML + CSS | No build step needed, instant GitHub Pages deploy |
| Tailwind CSS (CDN) | Utility-first styling, no npm required |
| Space Mono | Monospace font for technical aesthetic |
| Bebas Neue | Display font for headings |
| DM Sans | Body text readability |
| Schema.org JSON-LD | Structured data for Google rich results |
| Open Graph tags | LinkedIn/WhatsApp/Slack preview cards |

---

## 📧 Contact

**Ranjit Kumar Nayak**  
Lead RPA & Agentic AI Architect  
ranjit.nk@outlook.com · +91 97384 53661  
[linkedin.com/in/ranjitnk](https://linkedin.com/in/ranjitnk)

---

*Portfolio built for senior-level hiring. Designed to showcase architectural thinking and business impact — not just feature lists.*
