# Athar · أثر
**Interactive photography gallery · HTML / CSS / JavaScript**

[Back to profile](../README.md) · [Portfolio](https://badr-elfahm.github.io/Badr-Elfahm/#athar)

## The problem
A visual gallery needs to balance varied image sizes, a coherent browsing rhythm and access to the full original composition. Athar explores those choices through image-led navigation.

## The implementation
- Adaptive edge-to-edge image compositions.
- A gallery cycle that shows all 39 unique photographs before repeating.
- A full-image viewer and related-photo worlds.
- Navigation that restores the previous composition, scroll position and focus.
- Mobile layouts, keyboard navigation, Escape-to-close and reduced-motion support.

## Decisions and tradeoffs
Optimized WebP previews serve the gallery, while the viewer preserves each original image's full composition. Tags and color relationships guide related-photo navigation. Unknown location and date information stays blank.

## Verification and next steps
The project documentation records checks for composition order, duplicate-free initial cycles, viewer transitions, focus restoration and desktop/mobile overflow. Further checks can cover slow connections and long browsing sessions.

**Source access:** private. Photographs and source files are not redistributed by this overview.
