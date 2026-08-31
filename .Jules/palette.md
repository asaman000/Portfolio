## 2024-05-15 - Missing Accessible Close Buttons and Focus Outline
**Learning:** Found that custom modals often use text/html entities (like &times;) for close buttons and frequently miss aria-labels. Keyboard navigation (`:focus-visible`) was also globally missing across actionable elements.
**Action:** Implemented a global `:focus-visible` outline for buttons, inputs, links, and added `aria-label` to icon-only close buttons. Always check global `.css` files for a `focus-visible` rule when inspecting accessibility.
