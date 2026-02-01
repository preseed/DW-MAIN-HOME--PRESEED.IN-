# API Flow & External Integrations

This project integrates several third-party services and APIs to enhance functionality.

## Integrations Summary

| Service | File(s) | Purpose |
|---------|---------|---------|
| Google Analytics | `index.html`, `legal.html` | Visitor tracking and analytics. |
| Typeform | `startups/career.html` | Recruitment application widget. |
| YouTube Embed | `index.html`, `startups/index.html` | Narrative and educational videos. |
| Spotify Embed | `index.html` | "Preseed Voice" podcast episodes. |
| LinkedIn Embed | `index.html` | Professional social proof and updates. |
| Twitter Embed | `index.html` | Real-time updates from founder. |
| Google Fonts | `index.html`, `startups/index.html` | Typography (Sofia, Open Sans, etc.). |

## External Assets (CDN)
The project utilizes CDNs for libraries like Font Awesome, jQuery, and Bootstrap to ensure fast load times.

## Local Configuration
There are no backend APIs. All "flows" are client-side integrations via embedded `<script>` or `<iframe>` tags.
