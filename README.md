# Muhammad Subhan — Portfolio

A responsive, animated portfolio bringing together software development, AI projects and creative direction at PixelVerse.

## Content

Selected project case studies, category filters, an experience and education timeline, expandable capabilities, two CV downloads, and email/contact links. All professional information comes from the supplied CVs and reviewed GitHub repositories. Project artwork is a typographic presentation, not a screenshot of the applications.

## Source

`dist/index.html` contains the content, `dist/style.css` defines the responsive visual system, and `dist/app.js` implements dialogs, filters, motion preferences and copy-email feedback. Both CVs are in `dist/assets/`. The site has no runtime dependencies or build step. It uses optional Google Fonts with local fallback fonts.

Serve `dist/` with any static web server. Root-relative links are avoided, so it can also be hosted in a subdirectory. The Sites manifest configures `dist` as the static output.

## Accessibility and motion

Semantic sections, keyboard-operable controls, native modal dialogs, a skip link, visible focus states, reduced-motion media queries, and a pause-motion control. All core content is readable without JavaScript. Case-study dialogs and filters are progressive enhancements.

## Updating

Edit static content in `dist/index.html` and project narratives in `dist/app.js`. Review CV links, experience dates and project limitations before republishing. No contact form backend, analytics, payments or tracking is installed.
