### 1. **Functional Requirements:**
- **Display multiple tabs** (at least 3).
- **Clicking a tab** should **show its content** and **hide others**.
- **Active tab** should have a **different style** (highlighted).
- **Default**: First tab should be **active** when the page loads.
- **Support** switching tabs **without refreshing** the page.

---

### 2. **Technical Requirements:**
- Use **HTML**, **CSS**, and **Vanilla JavaScript** (no libraries like React, jQuery).
- Tabs should be **dynamic**: easy to add more tabs via HTML.
- **Clean and reusable** code (no duplication).
- Use **event listeners** to handle tab switching.
- Use **CSS classes** for showing/hiding tab content and active state.
  
---

### 3. **Bonus Features (Optional for extra points):**
- Keyboard navigation support (e.g., Left/Right arrows to move tabs).
- Smooth transition animations when switching tabs.
- Responsive design (tabs stack vertically on smaller screens).
- Allow **URL hash linking** to open a tab directly (`example.com#tab2`).

---

### 4. **Folder Structure:**
```
tabs-component/
├── index.html
├── style.css
└── script.js
```