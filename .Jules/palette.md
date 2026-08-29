## 2024-11-20 - Adding Accessibility Attributes

**Learning:** When reviewing vanilla HTML/CSS projects, we often find interactive elements (like modal close buttons containing only `&times;`) that lack `aria-label` attributes. Additionally, some form input labels (like "Proficiency Level" ranges) are grouped near their inputs but missing proper `for` attribute linkages.
**Action:** When updating vanilla HTML templates, systematically check all icon-only buttons for `aria-label`s and verify that all `<label>` tags correctly use the `for` attribute to reference their associated `<input>`s by ID.
