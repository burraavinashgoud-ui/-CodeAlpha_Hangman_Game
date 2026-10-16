# Hangman Game

## Run on GitHub Pages
This game is fully client-side and does not need Flask or a Python server.

1. Upload `index.html` and the `static` folder to your GitHub repository root, **or** keep the Flask folder structure and publish the included `index.html` plus `static/style.css`.
2. In `index.html`, change the stylesheet link to `static/style.css` if the file is at the repository root.
3. Enable GitHub Pages in **Settings → Pages** and select your deployment branch/folder.

## Run locally with Flask
Install Flask (`python -m pip install flask`) and run `python app.py` from this folder. Then open the local URL shown in the terminal. The browser game itself does not call Flask API endpoints, so it also works as a static site.
