# MOTION MOTOR

A cinematic, responsive automotive showroom built with plain HTML, CSS and JavaScript. No dependencies, installation, API keys or build step.

## Open the downloadable website

Extract the ZIP and open `index.html` in a modern browser. Keep `styles.css`, `app.js`, and the `assets` folder next to it. All photography is bundled locally, so the site also works offline.

Optional local server: run `python3 -m http.server 8080` inside the extracted directory and visit http://localhost:8080.

## Features

- Cinematic image reveal, pointer parallax, subtle lighting and scroll reveals.
- Horizontal vehicle collection with working previous/next controls.
- Combined marque, price, body type and year filters, result counts, empty state and reset.
- Vehicle detail dialogs with preselected viewing requests.
- Animated specifications, three switchable illustrative customer stories.
- Native accessible dialogs, keyboard controls, reduced-motion support, mobile navigation.
- Validated demo viewing form, browser-local request saving, downloadable text request and deletion control.

## Make it your dealership

1. Edit the `vehicles` array in `app.js` with verified stock, prices and specifications. Prices currently use illustrative USD amounts.
2. Replace representative photography in `assets`. Update descriptions and alt text to match exact stock.
3. Replace the illustrative customer stories with authorized real testimonials.
4. Add real showroom address, opening hours, telephone and email in `index.html`.
5. Connect the booking form to your backend, CRM or form service before accepting bookings. It currently saves only in the visitor's browser and does not send email or confirm appointments.
6. Replace the concept privacy statement with a policy that matches your production services.

## Design

Black and graphite surfaces, warm silver text, champagne accents and oversized modern sans-serif typography. Photography and parallax are intentionally used in place of a synthetic 3D vehicle. There is no real 360-degree model viewer.

## Photography

Bundled from Unsplash image endpoints, accessed November 17, 2026. Photographs are representative; vehicle trims/model years shown may differ from the illustrative listings. Review applicable image and trademark usage for your production context. No manufacturer affiliation is implied.

- Porsche: https://images.unsplash.com/photo-1503376780353-7e6692767b70
- Mercedes: https://images.unsplash.com/photo-1618843479313-40f8afb4b4d8
- BMW: https://images.unsplash.com/photo-1555215695-3004980ad54e
- Audi: https://images.unsplash.com/photo-1606664515524-ed2f786a0bd6
- Aston Martin: https://images.unsplash.com/photo-1507136566006-cfc505b114fc

## Hosting

Upload the extracted website files to any static hosting provider. In the source repository the web root is `dist/`; the downloadable ZIP places the same website at its top level for convenience.
