# Demo AI Web Patterns

This repository contains web components and patterns for use with AI-powered code generation tools. The following guidelines should be applied when generating code referencing this repository.

## Style Guidelines

**HTML Structure**

-   Use semantic HTML5 elements wherever appropriate (section, header, nav, main, etc.)
-   Include proper ARIA attributes for all interactive elements
-   Maintain clean, well-indented HTML with consistent spacing

**CSS/Styling**

-   Use utility classes from `utilities.min.css` instead of custom styles
-   Never include inline styles or separate `<style>` tags
-   Always use the `dx-*` prefix for classes from our design system
-   Apply responsive utilities with breakpoint prefixes (e.g., `md:dx-col-6`)
-   Default to mobile-first approach with desktop breakpoints added as needed

**Typography**

-   All headings should use sentence case (First word capitalized only), and be red text
-   Don't add extra margin classes to headings and paragraphs; they have base styles

**Components**

-   Always apply dx-w-full to cards to ensure proper width behavior
<!-- The above guideline should be removed once the .dx-card component has its 100% width style deployed. -->
-   Buttons should use RHDS components (rh-cta or rh-button)
-   Always include required JS imports for any RHDS components used

**Layout**

-   Apply responsive columns using the pattern: `dx-col-12 md:dx-col-6 lg:dx-col-3`
-   Maintain consistent spacing between sections using `dx-band` and appropriate margin utilities

**Colors**

-   Use semantic color utilities (e.g., `dx-bg-blue-50`, `dx-text-gray-90`)

**Accessibility Requirements**

-   Ensure all interactive elements are keyboard navigable
-   Include appropriate ARIA labels for icons and non-text interactive elements
-   Always add alt text to images (empty alt for decorative images)

**Performance Considerations**

-   Avoid unnecessary wrapper elements that add no semantic value
-   Keep the DOM structure as flat as possible while maintaining semantics

Following these guidelines ensures consistent, maintainable code that adheres to our design system standards.
