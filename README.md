# Pacer

A personal running app for iPhone (a home-screen web app in Safari). Load a route, and it splits it by gradient, sets a target pace for each section and gives live colour feedback against a gradient-adjusted target, with a per-km chart during the run and a report afterwards.

Live: <https://swhutchinson.github.io/pace-app/v4/>

| Folder | Version |
|---|---|
| `/` (root) | v1: gradient pacing, route matching, km splits and run reports |
| `v2/` | Race a gradient-aware virtual pacer |
| `v3/` | Tabs, training plans, insights learned from past runs, challenge links |
| `v4/` | Adds an optional AI coach that runs on your own laptop (`coach/`, Ollama) |

Each version is kept at its own address so older home-screen installs keep working. Plain HTML, CSS and JavaScript with no build step; tests run with `node --test tests/`.

A personal project, built with AI pair-programming (Claude Code).
