# Kipaxe website

Static site for Kipaxe Websites & Services. No build step — plain HTML/CSS/JS.

## Files
- `index.html` — the whole site (hero, work, services, process, packages, about, FAQ, contact)
- `404.html` — custom not-found page
- `styles.css` — all styling
- `assets/` — logo mark + project screenshots

## BEFORE YOU PUT IT LIVE

Search `index.html` for `[YOUR` and replace:
- `[YOUR EMAIL]` — appears 3 times (contact buttons + footer line)
- `[YOUR PHONE]` — appears 2 times

## Swapping in real screenshots

Three project images are branded placeholders until you replace them.
Take a screenshot of each site on your phone, then save it over the file
of the same name (keep the filename, it's already linked):

- `assets/tidybee-shot.jpg`  — The Tidy Bee
- `assets/abx-shot.jpg`      — ABX Hairdressing
- `assets/mckeown-shot.jpg`  — B&C McKeown (once it's live)

Portrait phone screenshots work best (roughly 620 x 1300). Anything close
to that shape will look right — they sit inside a phone frame drawn in CSS.

## Things worth checking before launch
- The stats band says "4+ sites built & running" — update if that changes.
- Prices in the Packages section are the ones we agreed; edit if they move.
- `B&C McKeown` card says "In progress / Coming soon" — swap the link when live.

## Hosting
Same as the Scenic Inn: push to GitHub, enable GitHub Pages, then point
kipaxe.co.uk at it in your domain registrar's DNS settings.
