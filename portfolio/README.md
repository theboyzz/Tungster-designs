# Portfolio

A static portfolio site. No build step.

## Structure

```
index.html                  Portfolio home page
games/hollow-ward/index.html   Hollow Ward, a browser horror game
```

## Edit

Open `index.html` and change the four spots marked `EDIT ME`: your name, the intro, your links, and the footer.

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `portfolio`.
2. Push these files to the `main` branch.
3. In the repository, open Settings, then Pages, and set the source to `main` and the folder to `/ (root)`.
4. The site goes live at `https://<your-username>.github.io/portfolio/`. Hollow Ward is at `/games/hollow-ward/`.

Name the repository `<your-username>.github.io` if you want the portfolio at the root of your GitHub address.

## Push from the command line

```
git init
git add .
git commit -m "Add portfolio and Hollow Ward"
git branch -M main
git remote add origin https://github.com/<your-username>/portfolio.git
git push -u origin main
```

## Hollow Ward

Controls: W A S D to move, arrow keys or mouse to turn, F or Space for the lamp, M for sound. Pacing is tuned in the `CFG` object at the top of the script in `games/hollow-ward/index.html`.
