## 2025-05-18 - Hover-Revealed UI Controls Keyboard Accessibility
**Learning:** Icon-only action buttons hidden with `opacity-0 group-hover:opacity-100` are invisible and inaccessible to keyboard users unless explicitly revealed when focused (`focus:opacity-100`).
**Action:** Always combine `group-hover:opacity-100` with `focus:opacity-100 focus-visible:ring-2` and descriptive `aria-label` attributes on table rows and slot item action buttons.
