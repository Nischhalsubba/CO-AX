# CO-AX Repository Overview

![CO-AX concept thumbnail](./assets/co-ax-thumbnail.svg)

## Classification

CO-AX is retained as a concept-brand landing-page reference. The repository currently contains documentation and a visual concept asset, but it does not contain the HTML, CSS, or JavaScript implementation described by the original project notes.

This distinction matters: the repository should not be presented as a deployed product or a runnable frontend until implementation source is restored or rebuilt.

## Intended frontend responsibilities

A restored implementation should stay deliberately small:

- **Page markup:** semantic structure for the hero, value proposition, call to action, contact/subscription area, and footer.
- **Styles:** responsive brand presentation, accessible focus states, readable contrast, and reduced-motion handling.
- **Interaction:** only the JavaScript needed for real behavior; avoid adding a framework solely for simple interactions.
- **Assets:** locally owned images/icons with verified licensing and optimized file sizes.

## Engineering rules

1. Keep the brand proposition and primary action clear.
2. Treat brand/business content as conceptual unless verified information is supplied.
3. Preserve local asset paths and filename casing.
4. Do not invent metrics, clients, testimonials, outcomes, or deployment claims.
5. Document each authored source file with its purpose and responsibilities when runtime code is reintroduced.
6. Document meaningful functions in plain engineering language, including important inputs, outputs, and side effects.
7. Prefer comments that explain intent or constraints over comments that merely narrate code syntax.

## Verification priorities

Before a restored implementation is published:

1. Verify the entry page and all referenced assets exist.
2. Test navigation, calls to action, and form/contact paths.
3. Check responsive behavior at phone, tablet, and desktop widths.
4. Test keyboard access, visible focus, contrast, and reduced motion.
5. Add accurate page metadata, favicon, and social-sharing metadata.
6. Confirm images and other media are licensed and optimized.
