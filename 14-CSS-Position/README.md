# 📍 CSS Position

Understanding the `position` property is crucial for elements that need to break out of the normal document flow, like fixed headers or sticky sidebars.

## 📝 Key Concepts Learned

### 1. **Static**

- Default behavior. Elements appear in order. `top`/`left` have no effect.

### 2. **Fixed Positioning**

- `position: fixed;`: Pins the element relative to the **viewport**. It stays in place when scrolling.
- Used for headers (`top: 0`) and bottom navigation bars.

### 3. **Sticky Positioning**

- `position: sticky;`: Acts as relative until a scroll threshold is met, then becomes fixed.
- Perfect for sidebar navigation or table headers.

### 4. **Z-Index**

- Controlling the stacking order of overlapping elements (e.g., header must be on top of content).

## 📂 Real-World Uses

- **Fixed Header**: Creating a navbar that follows the user.
- **Sticky Sidebar**: Keeping navigation visible while scrolling long content.

---

_Part of the HTML & CSS Full Course Practice._
