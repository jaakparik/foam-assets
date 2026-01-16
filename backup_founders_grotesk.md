## fonts

### Purpose
Contains web fonts for consistent typography across the application.

### Usage Rules
Use WOFF2 format for optimal web performance. Load fonts with proper font-display strategy.

### Special Notes
All fonts are Founders Grotesk family in WOFF2 format for web use.

> **Founders Grotesk** - Primary brand typeface for headings, body text, and UI elements.  
> **WOFF2 format** for optimal web performance and faster loading.  
> **Font weights available:** Light, Regular, Medium, Semibold, Bold.  
> **Styles available:** Normal and Italic for each weight.  
> Use with `font-display: swap` for better loading performance.

**Font Weights & Styles:**

**Light (300):**
- [founders-grotesk-light.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-light.woff2)
- [founders-grotesk-light-italic.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-light-italic.woff2)

**Regular (400):**
- [founders-grotesk-regular.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-regular.woff2)
- [founders-grotesk-regular-italic.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-regular-italic.woff2)

**Medium (500):**
- [founders-grotesk-medium.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-medium.woff2)
- [founders-grotesk-medium-italic.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-medium-italic.woff2)

**Semibold (600):**
- [founders-grotesk-semibold.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-semibold.woff2)
- [founders-grotesk-semibold-italic.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-semibold-italic.woff2)

**Bold (700):**
- [founders-grotesk-bold.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-bold.woff2)
- [founders-grotesk-bold-italic.woff2](https://proto.dev.foam.io/assets/fonts/founders-grotesk-bold-italic.woff2)

**Usage Guidelines:**
- **Light (300):** Subtle text, captions, secondary information
- **Regular (400):** Body text, paragraphs, general content
- **Medium (500):** Emphasis, subheadings, important text
- **Semibold (600):** Headings, titles, prominent text
- **Bold (700):** Main headings, hero text, strong emphasis
- **Italic variants:** Use for emphasis, quotes, or stylistic variation

**CSS Implementation:**
```css
@font-face {
  font-family: 'Founders Grotesk';
  src: url('https://proto.dev.foam.io/assets/fonts/founders-grotesk-regular.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
```