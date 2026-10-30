# CoreSuite Installer Replay

A replay of a CoreSuite first install on a fresh AlmaLinux 9 server, in the browser: the installer's questions as IT answers them, CoreNexus Hub and four apps (CoreInventory, CoreAttendance, CoreTask, CoreProject) installed and connected, and the final checks.

It is a simulation. The text is the installer's real output from test runs on 30 October 2026; keys, passwords and links are left out, and the first admin is sample data.

**Open it:** the published page, or `index.html` in any browser (one file; it loads only its fonts from Google Fonts).

## Publish with GitHub Pages

This repository is public. Under **Settings › Pages**, set **Source** to *Deploy from a branch*, **Branch** to `main` and the folder to `/ (root)`, then **Save**. GitHub shows the address after a minute, `https://<owner>.github.io/coresuite-replay/`.

## Update it

`index.html` is the whole page: the steps and their explanations are in `STEPS`, and the replayed screens and output in `SCRIPT`, both near the top of its script.
