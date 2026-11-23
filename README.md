# Daily 10 — Math Challenge

A responsive daily set of 10 original AMC/AIME-style math problems, with hints, answer checking, and saved progress, plus an interactive coordinate graphing studio.

## Run locally

Open `index.html` in a browser. The graphing studio is at `graphing.html`. The site has no build step or external dependencies.

The Daily 10 rotates through a repeating cycle of seven original practice-set variants at midnight in the visitor's local timezone. The site saves each date's set, answers, and progress in that browser's local storage; saved sets are not synced across devices.

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` enables GitHub Pages and deploys the site when changes are pushed to `main`.

Push a commit to `main`, or run the **Deploy to GitHub Pages** workflow manually from the Actions tab.

Once deployed, the site will be available at <https://selwindsouza11-gif.github.io/AMC/>.
