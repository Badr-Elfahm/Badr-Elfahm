# Traji · طراجي
**Arabic Morocco discovery guide · HTML / CSS / JavaScript / Node.js build tools**

[Back to profile](../README.md) · [Portfolio](https://badr-elfahm.github.io/Badr-Elfahm/#traji)

## The problem
A destination guide needs readable practical information and a way to compare and save places. Traji brings destination pages and trip-preparation tools into an Arabic interface.

## The implementation
- 21 destination pages with search and filters.
- Browser-local favorites and an interactive packing checklist.
- A responsive Arabic layout, image galleries and locally hosted WebP assets.
- A small Node.js build pipeline that generates HTML from destination data.

## Decisions and tradeoffs
Core destination content lives in HTML and remains readable without JavaScript. JavaScript adds discovery and saving features. Favorites and checklist state stay in the visitor's browser, without requiring an account.

Image attribution and license links are recorded in the project. Practical travel information has an editorial review date and still needs local confirmation before a trip; the project is a guide rather than a booking service.

## Verification and next steps
The repository documents build and content checks. Future improvements can focus on keyboard navigation, search empty states, small-screen layouts and a clearer content-review process.

**Source access:** private. This page describes the project; it does not publish its source or provide a live demo.
