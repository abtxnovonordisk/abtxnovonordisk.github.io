# abtx.in · How to update your website

This repository is your website. Anything you change here goes live on **https://abtx.in** about 1 to 2 minutes after you save it. Editing on github.com is free; you don't need any app.

## The files

| File | What it is |
|---|---|
| `index.html` | The whole website: all text, sections and layout |
| `Abhishek_Tomar_Resume.pdf` | The resume behind every "Download" button |
| `me.webp` | Your photo in the hero |
| `showreel.mp4` and `showreel-poster.jpg` | The showreel video and its cover image |
| `og-image.jpg` | The preview image shown when the link is shared on WhatsApp or LinkedIn |
| `CNAME` | Connects the site to abtx.in. **Do not edit or delete.** |
| `googlec6f504b5447b81c4.html` | Google Search Console verification. **Do not delete.** |
| `robots.txt`, `sitemap.xml`, `.nojekyll` | Settings for search engines and GitHub. Leave as they are. |

## Change some text

1. Open `index.html` and tap the pencil icon (**Edit this file**).
2. Press **Ctrl+F** (on a computer) and search for the words you want to change.
3. Change only the words. Keep everything inside `<` and `>` exactly as it is.
4. Tap **Commit changes**, then **Commit changes** again.

**Tip:** special characters are written as codes. Write `&amp;` for &, and keep `&nbsp;` where you see it.

## Where each section is in index.html

Search for these labels to jump to a section:

| Section on the site | Search for |
|---|---|
| Top menu | `class="links"` |
| Hero (your name and intro) | `class="hero` |
| Showreel | `id="reel"` |
| About me | `id="about"` |
| Omnichannel Engagement and brands | `id="oce"` |
| Selected work (FIB-4 and the six folders) | `id="work"` |
| Awards | `id="award"` |
| My Journey (education and roles) | `id="journey"` |
| Skills and tools | `id="toolkit"` |
| Contact | `id="contact"` |

## Add a new journey card

Inside `id="journey"`, each card is one `<article class="step" ...>` line. Copy a whole line that looks similar, paste it where it belongs in date order, and change the year, dates, title and text. Cards marked `class="step edu"` get the coloured border used for degrees.

## Replace a file (resume, photo, showreel)

1. Name your new file **exactly** the same as the old one, for example `Abhishek_Tomar_Resume.pdf`.
2. On the repository's main page, tap **Add file**, then **Upload files**.
3. Choose the file and tap **Commit changes**. It replaces the old file automatically.

For the photo, use a cut-out PNG or WEBP with a transparent background, about 600 px wide, saved as `me.webp`.

## If something breaks

Every save is kept. Open **Commits** (the clock icon on the main page), find the last version that worked, and open it to copy the old text back.

## Ongoing costs

- **GitHub hosting:** free.
- **abtx.in:** renews yearly at GoDaddy. Keep auto-renew on.
