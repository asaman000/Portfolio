## 2024-10-27 - Make Non-Semantic Interactive Elements Accessible
**Learning:** Many interactive elements (like modals and video thumbnails) in the project use `onclick` on `div`s. These are inaccessible to keyboard and screen reader users by default.
**Action:** When adding or modifying such elements, always include `role="button"`, `tabindex="0"`, and an `onkeydown` handler for Enter/Space keys (`if(event.key === 'Enter' || event.key === ' ') { event.preventDefault(); /* trigger action */ }`).
