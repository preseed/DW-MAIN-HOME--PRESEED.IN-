# Architecture Overview

This project is a static multi-page website serving as an ecosystem landing portal.

## Entry Points
- `index.html`: The primary entry point for the Preseed ecosystem.
- `startups/index.html`: The entry point for the startups-specific project showcase.

## Core Modules & Behavior
- **Layout**: Uses Bootstrap 3 for grid and responsive components.
- **Styling**: Custom CSS in `assets/css/style.css` and `assets/3.css`.
- **Navigation**: Uses `assets/js/grayscale.js` for smooth scrolling and navbar behavior on the root site.
- **Interactive Components**: 
  - jQuery-based modals and collapse/expand sections (FAQ-style).
  - External widgets for forms and embeds.

## Module Interactions
- **Assets**: Shared assets (CSS, JS, images) are stored in the root `/assets` directory.
- **Startups Sub-site**: The `/startups` directory acts as a semi-independent module with its own landing page and assets, though it references shared styles.

## Design Patterns
- **Monolithic HTML**: Most pages are large HTML files containing inline styles, internal `<style>` blocks, and jQuery scripts to manage UI state.
- **Fragmented Logic**: Behavior is often embedded directly within HTML files in `<script>` tags rather than separated into external modules.
