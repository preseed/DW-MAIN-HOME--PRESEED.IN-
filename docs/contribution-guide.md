# Contribution & Developer Guide

## Development Philosophy
This repository is primarily a static informational portal. Documentation and maintainability are prioritized to preserve the design and intent of the founder.

## Standards
- **Non-Destructive Changes**: Do not refactor existing logic or UI unless explicitly requested.
- **Documentation**: All new features or modules must be accompanied by updates to the `/docs` folder.
- **Commenting**: Use the standardized file headers and function documentation format.

### File Header Template
```html
<!--
  File: [Filename]
  Purpose: [Brief Description]
  Imports/Exports: [Dependencies]
  Interactions: [Key interactions with other files]
-->
```

### Script Documentation Template
```javascript
/**
 * [Description of the function]
 * @param {Type} name - Description
 * @returns {Type} - Description
 */
```

## Code Formatting
While no strict linting is enforced, maintain the existing indentation (mostly 4 spaces) to ensure consistency across the codebase.

## Local Testing
Always verify that links and embeds function correctly after any changes by serving the site locally.
