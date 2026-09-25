Personal Budget Tracker - Visual Identity (CSS)

A responsive, visually polished personal finance interface built with semantic HTML5 and modern CSS3.

Project Description

This project transforms a basic Budget Tracker web page into a modern, user-friendly web application. The design focuses on strong visual hierarchy, clean box-model spacing, accessibility, and modern UI practices without altering the underlying HTML structure.

Key Features & Visual Design Implementation

1. Intentional Color Palette

Primary Brand Accent (#0f766e - Deep Emerald Teal): Applied to major headings, primary submit buttons, table headers, and emphasis text to create visual cohesion.

Hover State Accent (#0d9488 - Bright Teal): Interactive elements provide clear hover feedback.

Page Background (#f1f5f9 - Soft Light Slate): A neutral gray/blue backdrop that reduces eye strain and helps content cards stand out.

Card Surface (#ffffff - Pure White): Clean white container backgrounds to maximize readability for form fields and table rows.

2. Custom Typography

Heading Font: Poppins (Semi-Bold & Bold) for strong, professional section titles.

Body Font: Inter for high legibility across input fields, table data, and form labels.

Hierarchy: Clear distinction in font sizes, weights, and line heights to guide user navigation effectively.

3. Effective Use of the CSS Box Model

Each major section is designed as a distinct visual card:

Margins (gap: 24px): Establishes consistent vertical spacing between sections.

Padding (28px): Creates breathing room inside card containers, input fields, and table cells.

Borders & Border-Radius (12px): Defines clean boundaries with modern rounded corners.

Shadows: Soft drop shadows give cards a subtle elevated appearance.

4. Table and Form Styling

Form Structure: Responsive CSS Grid layout with focus highlights (:focus) for interactive feedback.

Table Design: Solid high-contrast header, alternating zebra row background colors (:nth-child(even)), hover state feedback, and color-coded status badges for expense categories.

File Structure

budget-tracker/
├── index.html    # Semantic HTML structure containing header, form, and table
├── style.css     # Complete visual design rules and custom properties
└── README.md     # Project documentation and feature breakdown
