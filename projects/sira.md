# Sira · سيرة
**Multilingual CV builder · HTML / CSS / JavaScript**

[Live demo](https://badr-elfahm.github.io/sira-cv-builder/) · [Public source](https://github.com/Badr-Elfahm/sira-cv-builder) · [Back to profile](../README.md)

![Editor and live preview with demo data](https://raw.githubusercontent.com/Badr-Elfahm/sira-cv-builder/main/sira-preview.png)

## The problem
Preparing a CV often means switching between templates, language settings and a separate print view. Sira brings editing and an A4 preview into a standalone browser application.

## The implementation
The project combines a guided editor, ten templates, Arabic/French/English interfaces, right-to-left support, local saving, JSON backups, and PDF/PNG export. The application uses HTML, CSS and vanilla JavaScript without external runtime libraries.

## Decisions and tradeoffs
- Browser-local storage supports offline use; users need a JSON backup before clearing browser data or changing origins.
- Direct PDF export rasterizes pages, so its text is not selectable. The browser print route is available for text-based PDF output.
- Interface and heading languages are separate. Entered CV content is not automatically translated.
- The source and user guide document export behavior and browser-dependent limitations.

## Verification and next steps
The Arabic guide records earlier Microsoft Edge testing of local saving, import, templates and exports. A useful next step is a repeatable cross-browser check of Arabic text, page breaks, keyboard navigation, backup restoration and multi-page output.

[Read the full documentation](https://github.com/Badr-Elfahm/sira-cv-builder#readme)
