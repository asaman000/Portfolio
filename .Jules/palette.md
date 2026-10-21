## 2026-10-20 - Interactive Modals Missing Keyboard Support
**Learning:** Interactive UI components that use `onclick` on `div` elements completely lock out keyboard users, preventing them from accessing core content (like the portfolio showcase).
**Action:** When adding or fixing `onclick` events on non-semantic elements (`div`, `span`), always accompany them with `role="button"`, `tabindex="0"`, and `onkeydown` support for the 'Enter' and ' ' (Space) keys.
