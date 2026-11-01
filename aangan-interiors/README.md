# Aangan Interiors

A light, animated website for an interior design studio, built with React.

## Features

- Hero image slider with autoplay, arrows and progress dots. Visitors can add their own room photos.
- WhatsApp chat with a consultant (+91 91379 18782) with a pre-filled message, from the floating button, nav and hero.
- Interior cost estimator (home type, area, scope, finish level) that sends the estimate on WhatsApp.
- Consultation form that turns the visitor's answers into a WhatsApp message.
- Services, 5-step process, project gallery with filters, client stories, FAQ.
- Scroll and hover animations, respecting reduced-motion settings. Works on phones.

## Run it

It is a single `index.html` file. React loads from a CDN, so there is no build step.
Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Customise

Edit the constants at the top of the script in `index.html`:

- `WHATSAPP_NUMBER`, `WHATSAPP_DISPLAY`, `DEFAULT_MESSAGE`
- `SLIDES`, `SERVICES`, `STEPS`, `WORK`, `VOICES`, `FAQS`
- Estimator rates in `TIERS`, `ROOMS` and `SCOPES`

The studio name, prices, reviews and stats are sample content. Replace them with real details.
