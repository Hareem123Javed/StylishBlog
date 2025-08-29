

# StyleBlog

A modern, responsive, and theme-aware blog layout built using **HTML**, **CSS**, and **JavaScript**. The project demonstrates clean design principles, usability-focused layouts, and interactive features suitable for content-driven websites.

---

## 🎨 Design Approaches

### 1. **Theming with CSS Variables**

* Used `:root` variables to define core colors (`--primary`, `--secondary`, `--accent1`, etc.), ensuring consistency across the design.
* Implemented a **dark mode** toggle by redefining these variables under a `.dark-mode` class.
* This approach makes theming flexible and maintainable without rewriting component-specific styles.

### 2. **Responsive Layout**

* Designed using **flexbox** and **CSS grid** for adaptability.
* The main content is split into **posts** and a **sidebar** for larger screens, while smaller devices collapse into a **single-column layout**.
* Mobile navigation uses a **hamburger menu** and smooth slide-in animations for accessibility.

### 3. **Visual Hierarchy & Typography**

* Headings (`h1`, `h2`, etc.) use larger font sizes and accent colors for clear hierarchy.
* Content cards (posts, categories, widgets) emphasize readability with spacing, shadows, and rounded corners.
* Hover states on links and buttons improve discoverability and interactivity.

### 4. **Component-Based Design**

* **Header & Navigation**: Sticky header with logo, nav links, search toggle, theme toggle, and mobile menu.
* **Hero Section**: Split layout with engaging headline text and a feature image to grab attention.
* **Posts Grid**: Cards with images, meta-info, and hover effects for dynamic feel.
* **Sidebar Widgets**: Categories, trending posts, search, and social media links for engagement.
* **Newsletter Section**: Call-to-action styled with gradients and bold typography.
* **Footer**: Organized into multiple widgets for quick access to information.

### 5. **Color & Branding Strategy**

* Palette combines **deep purples, pinks, and soft accents**, creating a stylish yet professional aesthetic.
* Gradient backgrounds are used for **hero** and **newsletter sections** to add depth and modern appeal.
* Hover effects use accent tones to enhance visual feedback.

### 6. **Micro-Interactions & Animations**

* Posts fade-in with smooth transitions (`.fade-in` + JS intersection logic).
* Hover effects on cards, buttons, and social links provide a tactile, interactive feel.
* Back-to-top button appears with scroll, improving UX.

### 7. **Accessibility & Usability Considerations**

* Sticky navigation and scroll-margin ensure smooth in-page navigation.
* Color contrasts in dark/light mode support readability.
* Buttons and links have clear hover states for accessibility.
* Newsletter form uses required validation for better UX.

---

##  Features

* Light/Dark mode toggle.
* Responsive grid layout for articles.
* Interactive sidebar with categories, trending posts, and social links.
* Smooth animations and hover effects.
* Newsletter subscription form with CTA design.
* Back-to-top functionality for ease of navigation.

---


