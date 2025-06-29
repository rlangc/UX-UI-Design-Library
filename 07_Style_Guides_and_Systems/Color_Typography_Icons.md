# Color, Typography, and Icons

This file documents the core visual elements of your design system: color palette, typography, and iconography. Together, these assets build a cohesive and accessible visual identity.

---

## 🎨 Color Palette

### Primary Palette
| Name     | Hex       | Usage                       |
|----------|-----------|-----------------------------|
| Primary  | #007BFF   | Buttons, links, CTAs        |
| Secondary| #6C757D   | Labels, secondary text      |
| Accent   | #FFC107   | Warnings, highlights        |

### Utility Colors
| Name     | Hex       | Usage                       |
|----------|-----------|-----------------------------|
| Success  | #28A745   | Confirmations, success toasts |
| Danger   | #DC3545   | Errors, alerts              |
| Info     | #17A2B8   | Notifications, tooltips     |
| Light    | #F8F9FA   | Backgrounds, containers     |
| Dark     | #343A40   | Text, navigation            |

### Accessibility
- Maintain a contrast ratio of 4.5:1 or higher for all body text.
- Test using tools like Stark or WebAIM Contrast Checker.

---

## 🔤 Typography

### Font Stack
- Primary Font: `Inter`, `Helvetica Neue`, `Arial`, sans-serif
- System Font Fallbacks: `system-ui`, `Roboto`, `Segoe UI`

### Type Scale
| Style     | Size   | Weight   | Use                      |
|-----------|--------|----------|---------------------------|
| H1        | 32px   | Bold     | Page titles               |
| H2        | 24px   | SemiBold | Section headers           |
| H3        | 20px   | Medium   | Sub-section titles        |
| Body      | 16px   | Regular  | Paragraph text            |
| Caption   | 12px   | Regular  | Notes, tooltips, labels   |

### Spacing Rules
- Use 1.5x line height for body copy.
- Maintain 24–32px space between blocks of text.

---

## 🧩 Iconography

### Icon Library
- Use a consistent icon set (e.g., Heroicons, Feather, Font Awesome).
- Icons should:
  - Be vector-based (SVG)
  - Follow a common stroke weight
  - Align visually within a consistent bounding box (e.g., 24x24px)

### Usage Guidelines
- Use icons to support—not replace—text labels.
- Avoid using more than 1–2 icons per button or element.
- Maintain semantic meaning: 🗑 for delete, ✏️ for edit, 🔍 for search.

---

## ✅ Best Practices

- Apply color and type styles via design tokens or reusable styles in Figma.
- Ensure all visual elements scale responsively.
- Maintain legibility across light and dark modes.

---

These foundational elements support a clean, cohesive, and accessible design language across all screens and devices.
