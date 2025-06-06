# Demo AI Web Patterns

This repository contains web components and patterns for use with AI-powered code generation tools. The following guidelines should be applied when generating code referencing this repository.

## Style guidelines

**HTML structure**

-   Never include full HTML document structure (`<html>`, `<head>`, `<body>` tags)
-   Only provide code that would be contained within the body section
-   Use semantic HTML5 elements wherever appropriate (section, header, nav, main, etc.)
-   Maintain clean, well-indented HTML with consistent spacing

**CSS/Styling**

-   Never include inline styles or separate `<style>` tags
-   Always use utility classes from `utilities.min.css`
-   Always use the `dx-*` prefix for classes from our design system
-   Apply responsive utilities with breakpoint modifiers (e.g., `md:dx-col-6`)
-   Links should use their default styling, without additional classes, unless specified otherwise

**Typography**

-   All headings should use sentence case (First word capitalized only)
-   Don't add extra margin classes to headings and paragraphs; they have base styles

**Components**

-   Always use `rh-card` for card components, unless otherwise specified to use `dx-card`
-   Always apply dx-w-full to cards to ensure proper width behavior
<!-- The above guideline should be removed once the .dx-card component has its 100% width style deployed. -->
-   Buttons should use RHDS components (rh-cta or rh-button)
-   Always include required JS imports for any RHDS components used

**Layout**

-   Apply responsive columns using the pattern: `dx-col-12 md:dx-col-6 lg:dx-col-3`

**Colors**

-   Use semantic color utilities (e.g., `dx-bg-blue-50`, `dx-text-gray-90`)

Following these guidelines ensures consistent, maintainable code that adheres to our design system standards.
