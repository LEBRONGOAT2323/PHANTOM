# 👻 PHANTOM

A browser game-hub project with games, movies, music, and an account page. **This project is discontinued.**

> ## ⛔ Project status: Discontinued
> PHANTOM is **no longer maintained and will not receive any more updates.** Development has moved to **[THE PIZZA EDITION 2](https://github.com/LEBRONGOAT2323/THE-PIZZA-EDITION-2)**. This repo is kept as an archive of the work (54 commits).

**Live site (may be outdated):** `https://phantom-ubg.vercel.app`.

![PHANTOM screenshot](assets/images/screenshot.png)

---

## What it was

PHANTOM started as a side project with the goal of building a game hub with a more complete feel than a plain game list, including media pages and user accounts.

## Features

- 🎮 Games
- 🎬 Movies
- 🎵 Music
- 👤 Accounts
- ⚙ Settings
- 🔢 `version.json` for tracking site versions
  
## Run it locally

```bash
git clone https://github.com/LEBRONGOAT2323/PHANTOM.git
cd PHANTOM

python3 -m http.server 8000   # or: npx serve
```

Then open `http://localhost:8000`.

## Tech stack

- HTML, CSS, and vanilla JavaScript
- Vercel for hosting

## Project structure

| Path | Purpose |
|---|---|
| `index.html` | Home page |
| `g.html`, `a.html`, `s.html` | Games, Apps, and Settings |
| `movies.html`, `music.html` | Media pages |
| `account.html` | Account page |
| `subwaysurfers.html` | All subway surfers games page |
| `version.json` | Version info |
| `404.html` | Not-found page |
| `g/`, `a/` | Game and app files |
| `assets/images/` | Images |


## Why it was discontinued and what came next

PHANTOM is no longer being worked on. The ideas and lessons from it carried into [THE PIZZA EDITION 2](https://github.com/LEBRONGOAT2323/THE-PIZZA-EDITION-2), which is the current project.
From PHANTOM, I learned that having a lot of games isn't everything; using an external JSON file makes it convenient to add a bunch of games without spending hours adding them, but it comes with downsides.
When using an external source, it makes the games load incredibly slowly, and a lot of times the games don't even load. 


## Credits and game ownership

Games remain the property of their original creators. If you are a creator and want a game removed, please open an issue.

---

Built by [LEBRONGOAT2323](https://github.com/LEBRONGOAT2323).
