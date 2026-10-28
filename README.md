# Copilot x Sectors course site

The course website for **Build and Ship a Live IDX Stock App with an AI Pair Programmer**, the GitHub Copilot x Sectors Community Meetup (31 October 2026, Block71 Jakarta).

All text comes from the participant coursebook, `Coursebook - GitHub Copilot x Sectors Meetup.docx`. The page structure follows the Hermes-Material course site; the look follows the Algoritma design system.

## Pages

| File | Content |
| --- | --- |
| `home.html` | Introduction, learning path and module cards |
| `setup.html` | Prerequisites: set up before you arrive (P.1 to P.8) |
| `module-1.html` to `module-10.html` | One module per page |
| `resources.html` | Glossary and links to the tools |
| `assets/` | Algoritma logos and the three course diagrams |

Plain HTML and one shared `style.css`. No framework and no build step.

## Run it locally

```
npx serve
```

Then open the address it prints. `serve.json` turns on clean URLs (`/module-1` serves `module-1.html`) and sends `/` to `home.html`.

## Publish

Any static host works. On a host that does not read `serve.json`, set up the same two rules: clean URLs, and `/` to `home.html`.

Nothing in this site is investment advice.
