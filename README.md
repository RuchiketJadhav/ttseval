# PolyNorm TTS Evaluation Webpage

## Share with the team

Keep the whole folder together:

- index.html
- web_data.json
- audio/
- model audio folders copied from the original PolyNorm_tts output

Open `index.html` through a local web server (recommended), rather than double-clicking it.

Example:
```bash
cd /path/to/polynorm_team_web
python -m http.server 8000
```
Then open:
http://localhost:8000

Ratings are stored in each person's browser and can be exported with "Export ratings".

## Audio layout

The included `web_data.json` contains the exact relative WAV paths found in the uploaded ZIP.
