## 2024-10-11 - Accessibility on Icon-only buttons
**Learning:** Found multiple icon-only buttons (close modals, video lightbox, edit/delete actions) and icon-only links (social cards, live site links) without proper `aria-label`s. This is a crucial accessibility issue for screen readers.
**Action:** Always verify icon-only interactive elements (`<button>`, `<a>`) have clear, descriptive `aria-label` attributes.
