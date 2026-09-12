# Ganesh Chaturthi Invitation

A scroll-driven, single-page invitation. Implemented from the Claude Design source
`Ganesh Chaturthi Invitation.dc.html`
(project `eb05e408-e285-4981-beea-5690da050c98`), ported off the Claude Design
runtime (`x-dc` / `DCLogic` / `support.js`) into plain HTML, CSS and JS.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Markup for the three scenes: hero, invitation, details |
| `styles.css` | All styling, keyframes and reduced-motion handling |
| `app.js` | Scroll choreography, video autoplay nudge, share/map actions |
| `.claude/launch.json` | Local preview server on port 8765 |

## Configuration

Edit `CONFIG` at the top of `app.js`:

- `mapsUrl` — destination for the mushak / "Tap me for directions" tap target
- `showWhatsApp` — show or hide the share button
- `showPetals` — show or hide the falling petals in the details scene
- `shareMessage` — the WhatsApp share text (`mapsUrl` is appended)

Event details, venue and family name are plain text in `index.html`.

## Hosting

This repository is configured for GitHub Pages. Your site is live at:

**https://mahi140378.github.io/ganesh-invitation**

The meta tags in `index.html` are already updated with this URL for WhatsApp/social media previews.

## To Share

Simply share this link on WhatsApp, Facebook, or any social platform:

**https://mahi140378.github.io/ganesh-invitation**

The preview will display the garland image and invitation title.