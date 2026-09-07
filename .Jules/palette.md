## 2026-09-06 - Adding ARIA Labels to Icon-Only Buttons
**Learning:** In vanilla HTML templates, icon-only buttons (like modals or lightbox close buttons) are completely inaccessible to screen readers without ARIA labels. They just read as 'button', leaving users without context. This is a common pattern to watch out for in plain HTML/CSS projects without built-in accessibility safeguards.
**Action:** Always add descriptive `aria-label` attributes to any interactive element that relies solely on visual indicators (like an `&times;` or font icon) to convey its purpose.
