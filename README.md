# RK Empires Intelligent Automations — Landing Page

A single-file, self-contained landing page for **RK Empires Intelligent Automations** — a custom AI agency that builds and sells AI applications to help businesses save time, automate processes, and make more money.

**Tagline:** *Automate · Innovate · Elevate*

## What's here

```
rk-empires-landing/
├── index.html        # The entire site — HTML, CSS and JS in one file
├── favicon.ico       # Site icon (generated from the logo)
├── README.md
└── images/
    ├── RK Empires Logo Transparent.png            # Logo used in nav + footer
    ├── RK Empires Intelligent Automations Logo.png # Original logo (backup)
    ├── RK Empires Brand Guidelines.png            # Brand reference
    ├── favicon-180.png                            # Apple touch icon
    ├── testimonial-1.jpg                          # Testimonial photos
    ├── testimonial-2.jpg
    └── testimonial-3.jpg
```

## Brand

- **Colors:** metallic gold (`#d4af37`) on near-black (`#070707`)
- **Headings:** Playfair Display · **Body:** Montserrat (loaded via Google Fonts)

## Page sections

Hero → trust bar → problem → services → results/stats → process → testimonials → offer → FAQ → Calendly booking → footer. Structured to drive one action: **book a strategy call.**

## Booking

The booking section embeds **Calendly**: `https://calendly.com/rakaiservices/30min`
To change it, edit the `data-url` on the `.calendly-inline-widget` element in `index.html`.

## Run locally

Just open `index.html` in any browser. No build step. (Fonts, the Calendly widget, and live booking need an internet connection; everything else works offline.)

## Deployment

Hosted on **GitHub Pages**. Any push to the `main` branch publishes automatically.

## To do before paid traffic

- [ ] Replace the **fictional testimonials** with real client quotes
- [ ] Replace the **placeholder trust-bar company names** with real clients/logos
- [ ] Verify the Calendly event details are correct
