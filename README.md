# CoreSuite Installer Replay

Two replays of the CoreSuite installer on an AlmaLinux 9 server, in the browser:

- **First install:** the installer's questions as IT answers them, CoreNexus Hub and four apps (CoreInventory, CoreAttendance, CoreTask, CoreProject) installed and connected, and the final checks.
- **Update one app:** a later run that updates CoreAttendance: the clock check, a backup, its update, the apps connected again, and the checks.

It is a simulation. The text is the installer's real output from test runs on 30 October and 1 November 2026; keys, passwords and links are left out, and the first admin is sample data.

**Open it:** the published page, or `index.html` in any browser (one file; it loads only its fonts from Google Fonts).

## Publish with GitHub Pages

This repository is public. Under **Settings › Pages**, set **Source** to *Deploy from a branch*, **Branch** to `main` and the folder to `/ (root)`, then **Save**. GitHub shows the address after a minute, `https://<owner>.github.io/CoreSuite-Installer/`.

## Update it

`index.html` is the whole page: each replay has its steps and explanations (`STEPS`, `UPDATE_STEPS`) and its screens and output (`SCRIPT`, `UPDATE_SCRIPT`) near the top of its script, joined in `SCENARIOS`.
