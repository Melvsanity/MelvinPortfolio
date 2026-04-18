**Prompt:**

Create a single-page web portfolio using HTML, CSS, and vanilla JavaScript (no frameworks).

---

### Design Style

* Minimalist layout with a **vintage feel**
* Clean spacing with slightly warm, muted tones
* Subtle grain, texture, or soft gradients for depth
* Calm, smooth transitions
* Elegant and understated (avoid flashy effects)

---

### Color Palette

Use the following colors via CSS variables:

* Primary accent: `#ad0013` (deep vintage red)
* Secondary accent: `#a67d43` (muted gold/brown)
* Background base: `#121312` (dark charcoal)

**Usage guidance:**

* Use red sparingly for highlights and active states
* Use muted gold for borders, accents, and subtle emphasis
* Keep backgrounds dark and soft, not pure black
* Ensure good contrast and readability

---

### Layout Structure (1 page, 2 sections)

1. **Hero Section**

   * Name / title
   * Short tagline
   * Subtle background (soft gradient, faint grain, or vignette effect)

2. **Projects Section**

   * Clean grid or vertical list
   * Each project includes:

     * Title
     * Short description
     * Link placeholder

---

### UI Requirements

**Navigation Bar (Top Center)**

* Fixed at the top, centered horizontally
* Navigation items: Hero, Projects
* Styled as minimal pills:

  * Soft rounded edges
  * Thin borders using muted gold (`#a67d43`)
* Active section uses the red accent (`#ad0013`) subtly
* Smooth scrolling when clicked

---

**Theme Toggle (Top Right)**

* Minimal button design
* Switch between light and dark mode
* Persist preference using `localStorage`
* Smooth transition between themes

**Light Mode Adaptation:**

* Background: warm off-white / beige tone
* Accents remain consistent (red + muted gold)
* Maintain vintage warmth, not stark white

---

### Styling System

* Lightweight custom CSS system
* Use CSS variables for:

  * Colors
  * Spacing
  * Typography
  * Border radius
  * Shadows

**Typography:**

* Clean sans-serif for readability
* Optional subtle vintage touch (slight letter spacing or serif accent for headings)

---

### Interaction

* Smooth scrolling between sections
* Active nav updates on scroll
* Subtle hover effects:

  * Slight lift or scale
  * Soft color shift to red or gold
* Optional very light grain overlay or vignette for vintage atmosphere

---

header
add dark/ light mode toggle button at the top right corner
add logo placeholder with name Melvs 

Hero section i want is 

half left side full screen -  is for my profile section and 

half right side full screen  - is project preview
