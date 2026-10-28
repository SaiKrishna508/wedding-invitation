# Sai Krishna & Asha Latha — Digital Wedding Invitation

A lightweight, mobile-friendly Indian wedding invitation built with plain HTML, CSS and JavaScript. It includes an animated mandap illustration, falling petals, a royal maroon/gold floral palette, an English/Telugu toggle, a countdown, and an original synthesized instrumental-style loop that plays only after the visitor taps the music button.

**Wedding date:** Sunday, 22 November 2026. Guests are welcome from 6:00 PM, with the muhurtham at 8:49 PM (India time).
**Venue:** Mangalya Convention Hall, Opposite SBI, Gaigolapadu Junction, Andhra Pradesh 533005.

## Preview locally

1. Unzip the project (if you downloaded the ZIP).
2. Open `index.html` in Chrome, Edge, Safari or Firefox. Most features work directly from the file system.
3. Test the “Open our invitation” button, Telugu toggle and music button. Keep `assets/original-wedding-tune.wav` alongside `index.html` so the music loads.

## Before publishing — optional personalization

The confirmed ceremony time, venue, address and map link are already included. The countdown targets the muhurtham at 8:49 PM in India. You can still add parents' names, an RSVP/WhatsApp contact, reception details or a dress code if desired. Family name fields remain optional placeholders.

The cover currently uses “Sai Krishna” and “Asha Latha”; the browser page title and metadata use “Sai Krishna Satya Kumar” and “Asha Latha.” Change any wording you want to use consistently.

## Publish for free on GitHub Pages

1. Sign in to GitHub and create a **new public repository** named `wedding-invitation` (or any name you like).
2. Upload **the contents** of this project folder — `index.html`, `README.md`, `.nojekyll`, and the `assets` folder — to the repository root. Do not upload only the ZIP file.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the deployment to finish, then use the published address shown in Settings → Pages. It will usually look like `https://YOUR-USERNAME.github.io/wedding-invitation/`.
7. Open that URL on your phone and test it before sharing. A first publication or later updates can take a few minutes to appear.

GitHub Pages serves static files, so no Node.js build step or backend server is needed. The site loads Google Fonts over the internet; if the connection is unavailable, it falls back to locally available serif and sans-serif fonts.

## Notes

- Audio does **not** autoplay. Visitors must tap “Play our tune”; this is expected browser behavior and avoids surprising people with sound.
- The included tune is an original, programmatically synthesized, gentle pentatonic instrumental-style loop, not a recording of traditional instruments. It is included locally in `assets/` and does not depend on a third-party music stream.
- The page has no analytics, tracking pixels, server-side code or RSVP data collection.
- Use the reduced-motion system preference to reduce animations for visitors who request it.
- Check all names, times, spelling and venue links with both families before sharing the final invitation.

## Files

- `index.html` — complete site and styling.
- `assets/original-wedding-tune.wav` — original synthesized music loop.
- `.nojekyll` — asks GitHub Pages not to run Jekyll processing.
