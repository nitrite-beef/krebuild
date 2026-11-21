# KREBUILD (prototype)

A pixel-runner learning game for the full Krebs cycle (8 steps). One file, no installs: `index.html`.

## Run it on your computer
1. Download `index.html`.
2. Double-click it. It opens in your browser.

## Put it on GitHub Pages (free website link)
1. Sign in at github.com, click **New repository**, name it `krebuild`, set it to **Public**, click **Create repository**.
2. Click **uploading an existing file**, drag in `index.html` and `README.md`, then click **Commit changes**.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder to **/ (root)**, then click **Save**.
5. Wait 1 to 2 minutes. Your site is at `https://YOUR-USERNAME.github.io/krebuild/`.

## How to play
- Pick a runner. A 10:00 timer starts.
- The instruction box describes each molecule (for example, how many carbons it has).
- Drag the right structural formula into each box (on a phone, tap a structure, then tap the box).
- Click the center box to check. Wrong structures go back to the Ingredients box and cost 10 seconds.
- Each correct step zooms out, shows the cycle, and moves the runner forward. Finish all 8 steps to cross the finish line. If time runs out, the runner zooms in on its own screen, gasps for air, and a Try again button appears under it.

## Edit the content
- `C` in the script: the structures (atoms, bonds, branches).
- `ST`: the 8 steps (inputs, product, enzyme, note).
- Structure descriptions: `H`.
- Penalty: `hit(bad*10)`. Timer: `left=600`.
