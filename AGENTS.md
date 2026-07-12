# Repository Instructions

## Setup

CO-AX is a small static brand landing page. Serve the repository root with a static server after confirming the entry HTML file.

```bash
python -m http.server 8000
```

## Product conventions

- Keep one clear brand proposition and primary CTA.
- Treat current brand content as conceptual unless real business information is supplied.
- Keep sections short, responsive, and readable.
- Avoid adding dependencies for interactions that plain CSS or JavaScript can handle.
- Preserve local asset paths and filename casing.

## Verification

1. Load the entry page without console or network errors.
2. Test every navigation and CTA link.
3. Check mobile layout, focus, contrast, and reduced motion.
4. Verify title, description, icon, and Open Graph information.
5. Confirm all images are licensed and optimized.

## Do not

- Do not describe CO-AX as a live company or product without evidence.
- Do not invent metrics, clients, testimonials, or outcomes.
- Do not present the repository thumbnail as a runtime screenshot.
- Do not add a build system unless the project actually needs one.