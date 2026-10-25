# Ravens coaching simulator

This is the current playable version, packaged as one self-contained index.html.
No API key, npm install, build step or server is needed. The game runs in the browser.

## Publish on GitHub Pages

1. Unzip ravens-coaching-simulator-github.zip on your computer.
2. Open your GitHub repository. Select Add file > Upload files.
3. Upload index.html to the TOP LEVEL of the repository. Do not upload the ZIP itself, and do not nest index.html inside another folder. README.md and .nojekyll are optional uploads.
4. Commit the upload to main. Replace the old index.html if updating an existing game.
5. In Settings > Pages, choose Deploy from a branch, select main and / (root), then Save.
6. Open the published link shown in Pages after deployment finishes. Hard-refresh if the old version is cached.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Try it before uploading

Double-click index.html to open it in a browser. All gameplay works offline. Copy result may need HTTPS (GitHub Pages provides it) or clipboard permission.

## Included features

- Real 2026 halftime scenarios: Tyler Huntley against Cincinnati (13-0) and Cleveland (10-0), and Lamar Jackson against New Orleans (14-6).
- Short stretches of up to three snaps, with frequent offensive and defensive choices.
- Automatic routine punts and player-controlled meaningful fourth downs.
- Opponent efficiency profiles and adjustments for repeated approaches.
- Score-aware two-point tries, timeouts, fourth downs and onside kicks.
- Simulate the rest of the game, restart, quit and immediate scenario switching.
- Field position display, game log, local win record and copyable results.

## Ratings and limitations

Team profiles use a fixed Sharp Football Analysis Week 7 efficiency-ranking snapshot captured Oct. 25, 2026. These rankings blend success rate and EPA and adjust for opponents; they are not DVOA. The same snapshot applies to all starting scenarios. Rank-to-probability mappings are game design, not calibrated NFL win probabilities.

The starting score, quarterback and receiving team are historical. Subsequent plays and kickoff returns are simulated. Games end after regulation; ties do not count as protecting the lead. Local records belong to the browser and website origin, so records from the private preview do not transfer to GitHub Pages.

Independent fan game; not affiliated with the Ravens or NFL.
