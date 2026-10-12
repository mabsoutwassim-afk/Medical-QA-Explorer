## 2024-10-12 - Scrollable Region Keyboard Accessibility & ARIA Live Regions
**Learning:** Scrollable containers with overflow text require `tabindex="0"`, `role="region"`, and `aria-label` to allow keyboard-only users to focus and scroll using arrow keys. Dynamic content updates require `aria-live="polite"` and `aria-atomic="true"` for screen readers to announce changes automatically.
**Action:** Always make scrollable containers focusable and labeled, and ensure live feedback areas have `aria-live` attributes.
