## Live Page :link:

You can find the live version of the code at the following link: https://keskenridvan.github.io/goit-markup-hw-04/

---

# GoIT Homework Content ✨

**This document outlines the essential requirements for setting up and developing this project. Adhering to these guidelines ensures consistency, maintainability, and proper deployment on GitHub. 🚀**

---

## Homework Assignment (HW-04) 📚

- Create a new GitHub repository named `goit-markup-hw-04`.
- Copy the files from your previous work into this new repository.
- Add icons and decorative effects to the design as specified in [Homework #4](https://www.figma.com/design/wuEpGhwCepGCOUw7mZFRac/Web-Studio--Version-5.0-?node-id=297016-823).
- Utilize [Icomoon](https://icomoon.io/) service to create SVG sprites.
- Use [svgomg](https://jakearchibald.github.io/svgomg/) service to optimize the created SVG sprite.
- Set up `GitHub Pages` and add a link to the live page in the About section of your GitHub repository.

---

## Project Structure & Setup 📁

- **A1:** An `images` folder must be present in the project's root directory, containing all project visuals. 🖼️
- **A2:** All vector `images` (icons) must be collected in the SVG-sprite `icons.svg` file located within the `images` folder.
- **A3:** All vector `images` must be optimized. ⚙️
- **A4:** A `css` folder must be present in the project's root directory, containing all stylesheet files. 🎨
- **A5:** All styling rules must be written in the `styles.css` file located within the `css` folder. ✍️
- **A6:** File names must not contain uppercase letters, spaces, or special characters. Names should consist only of English letters and words. 🔠
- **A7:** The source code must be formatted using `Prettier`. ✨
- **A8:** All `images` and text content must be accurately extracted from the layout. ✂️
- **A9:** `modern-normalize` must be enabled as a style normalizer. 📏
- **A10:** All styles must be written in the `styles.css` file located within the `css` folder. (This appears to be a duplicate of A5, but included as per your original text). ✍️
- **A11:** The code must be written in compliance with established coding [guidelines](https://codeguide.co/). ✅

---

## Markup (HTML) 📝

- **B1:** All icons must use vector graphics in `SVG` format. 🏞️
- **B2:** SVG icons must be exported correctly. When exporting, "group" should be selected instead of the vector itself. 🔗
- **B3:** All icons in the SVG sprite must be added to HTML using `<svg>` and `<use>` tags. ⚙️
- **B4:** Icons must be added to the "Advantages" section (an untitled section containing a list of advantages above `"Our Team"`). ✨
- **B5:** Social media icons must be added to the "Our Team" section. 🧑‍🤝‍🧑
- **B6:** (Missing B6 from your original text, renumbered for clarity if needed, or left out if intentional)
- **B7:** Social media icons must be added to the footer. 🦶
- **B8:** All design elements must have completed HTML structuring. 🏗️
- **B9:** HTML tags must be used according to their semantic content. 💡

---

## Styling (CSS) 💅

- **C1:** A large background image must be used under the header. The background should have a multi-layered design with a fading effect and a gradient. 🌄
- **C2:** The background image in the block under the header should not extend beyond its original size of `1440px`. 📐
- **C3:** Cards in the `"Our Team"` section must have a persistent shadow effect. 👥
- **C4:** Cards in the `"Our Portfolio"` section must display a shadow effect when hovered over anywhere on the card. 🖼️
- **C5:** When hovered over or focused, icons should transition to an active state – changing color if specified in the layout. 🖱️✨
- **C6:** Transitions must be applied for all hover and focus effects (color, background, shadow). Time: `250ms`, `timing function: cubic-bezier(0.4, 0, 0.2, 1)`. ⏳
- **C7:** Transitions must explicitly specify animated properties. An `all` value should not be used anywhere. 🚫
- **C8:** In the main navigation, the link to the current page (where the user is currently located) must be underlined using the `::after` pseudo-element. 📍
- **C9:** In the `"Our Portfolio"` section, an overlay with text must appear on cards when hovered over anywhere on the card. 📖
- **C10:** The blue overlay on cards in the `"Our Portfolio"` section must be pressed to the bottom. ⬇️
- **C11:** Pseudo-elements should not contain text content in their `content` property. They should be used for decorative purposes only. 🖼️
