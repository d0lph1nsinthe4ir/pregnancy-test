# Gestimate

**Gestimate** is a lighthearted, mobile-friendly guessing game that estimates how many weeks pregnant someone might be based on their symptoms.

## Play

Open the website and answer up to 20 questions. The questions adapt to prior responses, and the game guesses a gestational week and a plausible range. Players can reveal their actual week to see how close the estimate was, go back to revise an answer, skip questions, or play again.

The game includes deliberately silly Easter-egg results for unexpected answers, including "You are a man," "You are not pregnant," "You are the baby," and "You are literally giving birth."

## Technical details

- Built as a single HTML file (`index.html`), with embedded CSS and vanilla JavaScript.
- No frameworks, build pipeline, backend, paid services, cookies, analytics, or account required.
- Answers are used only in the running page; they are not sent to a server or saved.
- The layout adapts to narrow mobile screens.
- The estimation algorithm uses a heuristic symptom likelihood model; **it is not a validated pregnancy dating tool or pregnancy test**.

## Run locally

Open `index.html` in a modern web browser. An internet connection is not needed for the game itself.

## Publish for free with GitHub Pages

1. Keep `index.html` and `.nojekyll` at the root of the `main` branch.
2. In the GitHub repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**. Set branch to **main**, folder to **/(root)**, and save.
4. Once GitHub reports a successful deployment, the expected address is: https://d0lph1nsinthe4ir.github.io/pregnancy-test/

The website address is not confirmed live until GitHub Pages has successfully published it.

## Disclaimer

For entertainment only. Symptoms vary substantially; the game's output does not establish pregnancy or gestational age. Clinical dating is more reliable.
