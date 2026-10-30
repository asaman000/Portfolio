## 2026-10-30 - Keyboard Accessibility on Video Modals
**Learning:** Found `div` elements acting as buttons (`onclick`) for video thumbnails and tablet screens without proper keyboard accessibility (`role="button"`, `tabindex="0"`, and keydown handlers).
**Action:** Always add keyboard accessibility attributes and event listeners when using non-semantic elements for interactive components.
