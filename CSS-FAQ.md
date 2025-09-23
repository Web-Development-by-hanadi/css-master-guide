# ❓ CSS FAQ

A collection of frequently asked questions and answers about CSS.

---

### 1. What is the difference between `text-align` and `direction`?
- **`text-align`**: Controls horizontal alignment of inline content inside a block (`left`, `right`, `center`, `justify`).  
- **`direction`**: Defines the writing direction (`ltr` for left-to-right, `rtl` for right-to-left).

---

### 2. What is the difference between `em`, `rem`, and `px`?
- **`px`**: Fixed size in pixels (does not scale).  
- **`em`**: Relative to the font-size of the parent element.  
- **`rem`**: Relative to the font-size of the root element (`html`).

---

### 3. Difference between `relative`, `absolute`, `fixed`, and `sticky` positioning?
- **Relative**: Element is positioned relative to itself.  
- **Absolute**: Positioned relative to the nearest positioned ancestor.  
- **Fixed**: Stays fixed relative to the viewport, even on scroll.  
- **Sticky**: Acts like relative, but becomes fixed when a threshold is reached while scrolling.

---

### 4. Difference between `inline`, `block`, and `inline-block`?
- **Inline**: Does not start on a new line, takes only necessary width.  
- **Block**: Starts on a new line, takes full available width.  
- **Inline-block**: Behaves like inline, but allows setting width/height.

---

### 5. What is the difference between `id` and `class` selectors?
- **ID (`#id`)**: Unique, should be used only once in a page.  
- **Class (`.class`)**: Can be used multiple times on different elements.

---

### 6. What is the difference between `min-width`, `max-width`, and `width`?
- **width**: Sets a fixed width.  
- **min-width**: Ensures the element never gets smaller than this value.  
- **max-width**: Ensures the element never gets larger than this value.

---

### 7. What is the difference between `relative units` and `absolute units`?
- **Relative units**: Depend on other values (`em`, `rem`, `%`, `vw`, `vh`).  
- **Absolute units**: Fixed sizes (`px`, `cm`, `mm`, `in`).

---

### 8. What is the difference between `position: static` and `relative`?
- **Static**: Default position, not affected by top/right/bottom/left.  
- **Relative**: Positioned relative to its normal flow position.

---

### 9. What is the difference between `inline CSS`, `internal CSS`, and `external CSS`?
- **Inline**: Applied directly in the element’s `style` attribute.  
- **Internal**: Written inside a `<style>` tag in the HTML `<head>`.  
- **External**: Stored in a separate `.css` file and linked with `<link>`.

---

### 10. What is the difference between `z-index` and stacking order?
- **z-index**: Controls the stack order of positioned elements.  
- **Stacking order**: The natural order without `z-index` (later elements in the DOM appear on top if overlapping).
