# Global AI Adoption in Education — Tableau Web Integration

## Overview
Interactive Tableau analysis of global AI adoption in education for 2015–2026, covering student usage, teacher usage, school adoption, regional differences, popular AI tools, urban–rural usage, curriculum integration, and government AI policy.

## Stack
- Tableau / Tableau Public
- Python + Flask
- Gunicorn
- HTML/CSS
- Render

## Repository
```text
GlobalAI_WebIntegration/
├── app.py
├── requirements.txt
├── .gitignore
└── templates/
    └── index.html
```

## Run locally
```bash
pip install -r requirements.txt
python app.py
```
Open `http://127.0.0.1:5000`.

## Public links
- GitHub: https://github.com/jeetpal-tech/GlobalAI_WebIntegration
- Live web app: https://globalai-webintegration.onrender.com
- Tableau Public: https://public.tableau.com/app/profile/jeet.pal7266/viz/GlobalAIAdoptioninEducation_/Story1?publish=yes

## Tableau Story
Seven scenes cover: global challenge, regional disparity, 2015–2026 trends, tool competition, urban–rural equity, student-vs-teacher adoption, and conclusions/recommendations.

## Deployment
Render uses:
- Build: `pip install -r requirements.txt`
- Start: `gunicorn app:app`

The Flask page embeds the public Tableau Story in an iframe.
