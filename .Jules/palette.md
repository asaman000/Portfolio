## 2026-10-12 - Adding ARIA labels to dynamically rendered buttons
**Learning:** When dealing with dynamic UI rendering (like mapping through an array of objects to generate table rows in vanilla JS), adding static ARIA labels to icon-only buttons isn't enough. Screen reader users need context about *which* item they are modifying.
**Action:** Always interpolate unique identifiers or descriptive properties from the data object (e.g., `${item.name}` or `${item.title}`) into the `aria-label` when generating icon-only action buttons dynamically.
