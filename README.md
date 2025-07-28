# Contact Manager UI

A simple Android UI screen designed to simulate a contact manager interface. This task is part of the **Android Mini Project Series** and focuses purely on XML layout design using modern UI and resource management practices.

---

## 🎯 Objective

Create a static contact management screen using:
- `ConstraintLayout` and `LinearLayout`
- Reusable resources: colors, strings, dimensions
- Best UI attribute practices for spacing, readability, and theming

---

## 🧱 Layout Structure

- Root: `ConstraintLayout`
- Nested: `LinearLayout` for vertical stacking
- Elements included:
  - 🖼️ `ImageView` (`ivContactImage`) – contact profile image
  - 📛 `TextView` (`tvContactName`) – displays contact name
  - 📝 `EditText` (`etContactNotes`) – note field
  - 💾 `Button` (`btnSaveContact`) – save action

---

## 🎨 Starry Night Theme

This screen uses a Van Gogh–inspired palette defined in `colors.xml`:

| Color Name     | Use Case         |
|----------------|------------------|
| `deepBlue`     | Background        |
| `skyBlue`      | Buttons, input tint |
| `moonYellow`   | Header text       |
| `cloudWhite`   | Text & hint color |

---

## 📦 Resource Management

| Resource Type | File | Example |
|---------------|------|---------|
| Strings       | `strings.xml` | `@string/save_contact` |
| Colors        | `colors.xml`  | `@color/deepBlue` |
| Dimensions    | `dimens.xml`  | `@dimen/default_padding` |
| Drawables     | `drawable/van_gogh.jpg` | Profile image placeholder |

---

## ✅ Attribute Practice

Applied UI attributes:
- `textSize` for readability
- `textColor` and `backgroundTint` for theme
- `layout_margin` and `padding` for spacing
- `gravity` and `scaleType` for alignment

---


## 🚀 Learning Outcomes

- XML layout nesting and structure
- ID naming conventions (`tvContactName`, `btnSaveContact`, etc.)
- Resource-driven styling (no hardcoded values)
- Theming and accessibility considerations

---

