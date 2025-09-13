# SPARKE Constructions — Static Website

A fast, responsive static website scaffold for the new SPARKE Constructions brand. Includes a shared theme, reusable layout, animated hero, and content pages: Home, About, Services, Projects, Contact.

## Structure

```
/ (project root)
  index.html
  about.html
  services.html
  projects.html
  contact.html
  /assets
    /css
      reset.css
      theme.css
      layout.css
      home.css
    /js
      main.js
      home.js
    /img
      placeholder-hero.svg
      placeholder-project.svg
```

## Getting Started

Open `index.html` in a browser. No build step is required.

## Theming

Update CSS variables in `assets/css/theme.css` to match the exact SPARKE Constructions palette:

```css
:root {
  --brand-primary: #0E2A47; /* replace with exact brand color */
  --brand-accent:  #FDB515; /* replace with exact brand accent */
  --brand-muted:   #6C7A89; /* secondary text */
  --bg:            #0B0F14; /* page background */
  --surface:       #111723; /* cards/nav/footer */
  --text:          #EAEFF5; /* main text */
}
```

## Accessibility

- Respects `prefers-reduced-motion`
- High-contrast palette and focus-visible outlines
- Semantic HTML landmarks and labels

## Contact Form

The contact page uses a `mailto:` based form by default to keep it fully static. You can swap it for a hosted form backend (e.g., Netlify Forms, Formspree) by replacing the form `action` in `contact.html`.

## License

MIT