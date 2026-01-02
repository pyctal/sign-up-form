# Sign-up Form

![Status](https://img.shields.io/badge/Status-Completed-success)
![Focus](https://img.shields.io/badge/Focus-Form_Validation_%26_Layout-blue)

## Description

This project is a recreation of a modern sign-up page design.

The goal was to move beyond basic document flow and build a split-screen layout that combines rich media (background images, custom typography) with a functional, styled data entry interface. It focuses heavily on form aesthetics, custom input behaviors, and HTML5 client-side validation.

## Features

- **Split-Screen Layout:** A responsive design featuring a visual sidebar with a background image and a main content area for the form.

- **Custom Typography:** Integrates a custom font face ("Oughter") for branding elements.

- **HTML5 Validation:**

  - **Required Fields:** Prevents submission if fields are empty.
  - **Pattern Matching:** Enforces valid phone number formats using Regex patterns (`pattern="^[+]?{1}..."`).
  - **Input Types:** specific types for `email`, `tel`, and `password` to trigger correct browser behaviors.

- **Visual Feedback:**

  - **Focus States:** Custom blue borders and drop shadows highlight the active field.
  - **Error States:** Password fields display a red border when the input is invalid.

- **Submission Handling:** Configured to POST data to `httpbin.org` for testing successful form data transmission.

## Skills Demonstrated

By completing this project, I have demonstrated proficiency in the following areas:

### 1. Intermediate CSS Layouts

- **Flexbox Architecture:** Utilized flexbox properties to create a fluid 2-column layout that fills the viewport height.
- **Absolute Positioning:** Placed the logo overlay on top of the background image using `position: absolute` relative to the sidebar container.
- **Flex Wrapping:** Enabled `flex-wrap` on form rows to ensure inputs stack or sit side-by-side depending on available space to improve website responsiveness.

### 2. Form Styling & User Experience

- **Pseudo-Class Targeting:** extensive use of `:focus` to remove default browser outlines and apply custom branding, and `:invalid` to provide immediate visual feedback on errors.
- **Box Model Management:** Applied `box-sizing: content-box` specifically to inputs to strictly control their dimensions alongside `border-box` for the layout.
- **Aesthetics:** Implemented `box-shadow` for depth on cards and buttons, and managed background opacity for text readability.

### 3. Asset Management

- **Custom Fonts:** Loaded local font files using the `@font-face` rule.
- **Background Images:** Managed background sizing (`cover`) to ensure the sidebar image scales correctly without distortion.
