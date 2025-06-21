# art-of-maps-2
Presentation on Art of Maps Episode 2

## Install Dependencies

```
pip install -r requirements.txt
```

## Build Presentation

```
jupyter nbconvert presentation.ipynb --to slides --reveal-prefix="https://unpkg.com/reveal.js@4.0.2" --output
```

## Preview Presentation

```
python -m http.server 8000
```

Navigate to http://localhost:8000/presentation.slides.html#/ to preview locally

[![Netlify Status](https://api.netlify.com/api/v1/badges/f66eb174-e098-4201-8d0e-5a857820d598/deploy-status)](https://app.netlify.com/projects/art-of-maps-2/deploys)
