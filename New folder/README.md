# Sonics DayZ Editor

A fully ready-to-run DayZ editor with:
- types.xml editor (nominal +1 → +5, auto-fix count_in_map)
- events.xml editor (+1 / +5 / +10 for all values)
- JSON and XML validation
- Apocalyptic UI with zombie Sonic logo (placeholder)

## How to Use Locally
1. Open `index.html` in a browser
2. Paste your `types.xml` or `events.xml`
3. Click buttons to adjust values
4. Copy or save the edited XML

## How to Deploy to Cloudflare Pages
1. Push this repo to GitHub
2. Go to https://dash.cloudflare.com/pages → Create a project
3. Connect your GitHub repo
4. Framework preset: **None**  
5. Build output directory: `/`  
6. Deploy → live URL generated
