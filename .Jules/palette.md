## 2026-10-17 - [UX/A11y Opportunities]
**Learning:** Found multiple custom modal close buttons (using `&times;`) without ARIA labels, making them inaccessible to screen readers. Focus-visible states are also missing globally, harming keyboard accessibility.
**Action:** Add `aria-label="Close"` to these buttons and implement a global `:focus-visible` CSS rule.
