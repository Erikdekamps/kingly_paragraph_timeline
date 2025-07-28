# Kingly Timeline Paragraph

Installs a responsive, accessible, and configurable timeline paragraph.

## Overview

This recipe creates two new paragraph types:

1.  **Kingly Timeline:** The main container for the timeline. It includes a field to select the orientation (vertical or horizontal).
2.  **Kingly Timeline Item:** A paragraph for an individual event in the timeline. It includes fields for a date, title, description, and an optional link.

The frontend rendering is powered by the `kingly_minimal:timeline` Single Directory Component (SDC), which uses modern CSS for robust, accessible, and responsive layouts.

## Features

*   **Configurable Orientation**: Editors can choose between a vertical or a horizontal layout.
*   **Accessible by Design**: Built with semantic HTML and ARIA attributes to be WCAG 2.1 AAA compliant.
*   **Responsive**: The horizontal layout becomes a touch-friendly scrollable container on smaller viewports.
*   **Component-Driven**: All markup and styling is encapsulated within the SDC for maximum maintainability.

## Dependencies

This recipe requires the following:

*   `kingly_page` recipe (for content placement).
*   `kingly_minimal` theme (for the required `timeline` SDC).
