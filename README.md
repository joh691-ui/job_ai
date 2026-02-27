# 🚀 JobSearch AI — Streamlit

Automatiserad jobbsökning via **JobTech API** med AI-matchning (Gemini / g4f).

## Deploy på Render

1. **Pusha filerna till ett GitHub-repo** (eller ladda upp direkt)

2. **Skapa ny Web Service på [render.com](https://render.com)**:
   - **Build Command:** `chmod +x build.sh && ./build.sh`
   - **Start Command:** `streamlit run app.py`
   - **Environment:** `Python 3`
   - **Plan:** Free tier funkar

3. **Klart!** Appen startar på `https://ditt-namn.onrender.com`

## Lokal körning

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Funktioner

- 🔍 Söker jobb via Sveriges öppna JobTech API
- 🤖 AI-analys med Gemini (snabb, parallell) eller g4f (gratis, sekventiell)
- 📊 Sorterade resultat med poäng och motivering
- 📥 Excel-export med dark mode-formatering
