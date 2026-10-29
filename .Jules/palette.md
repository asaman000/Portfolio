## 2024-10-30 - Accessible Div Buttons
**Learning:** Interactive elements like modals and video thumbnails in this project are often implemented as `div` elements with `onclick` handlers. These are completely inaccessible to keyboard users and screen readers out of the box.
**Action:** When adding or modifying interactive `div`s, always remember to add `role="button"`, `tabindex="0"`, `aria-label`, and an `onkeydown` handler for the Enter and Space keys to ensure full keyboard and screen reader accessibility.
