## 2024-05-14 - Interactive Divs and Keyboard Accessibility
**Learning:** Many interactive elements (like modals and video thumbnails) in the project use `onclick` on `div`s without proper keyboard accessibility support, which causes problems for screen readers and keyboard users.
**Action:** When adding or fixing these, ensure keyboard accessibility by including `role="button"`, `tabindex="0"`, `aria-label`, and `onkeydown` handlers for Enter and Space keys.
