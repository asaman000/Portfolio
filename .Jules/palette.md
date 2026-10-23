## 2026-10-23 - Making Div-based Buttons Accessible
**Learning:** When using `div` elements as interactive buttons (e.g., clicking on a video thumbnail or tablet screen), screen readers and keyboard users cannot interact with them by default as they lack semantic meaning and keyboard focus.
**Action:** Always ensure keyboard accessibility and semantic meaning by adding `role="button"`, `tabindex="0"`, and an `onkeydown` handler (to support Enter/Space keys) to any `div` that uses an `onclick` handler.
