### Project: **Accordion Menu**

### Objective:
Create a smooth, responsive accordion menu using **HTML, CSS, and JavaScript** where clicking a section header expands or collapses the content below it.

---

### Functional Requirements:
1. **Expand/Collapse Behavior**:
   - When a menu header is clicked, its corresponding content should expand.
   - If another section is already open, it should automatically collapse (only one open at a time).
   - Clicking an already open header should collapse it.

2. **Multiple Sections**:
   - The menu should have at least **4 sections** (you can have more).

3. **Animations**:
   - Smooth transition animation when expanding/collapsing sections (use CSS transitions).

4. **Accessibility**:
   - Allow users to navigate with the **keyboard** (optional for bonus points).
   - Use proper **ARIA attributes** (`aria-expanded`, `aria-controls`).

5. **Initial State**:
   - All sections should be **collapsed** when the page loads.

6. **Responsiveness**:
   - It should work properly on **mobile**, **tablet**, and **desktop**.

---

### Technical Requirements:
- Use **vanilla JavaScript** (no libraries like jQuery).
- Clean **HTML5** structure.
- **CSS3** for styling and transitions.
- No page reloads.

---

### Bonus Features (Optional if you want to make it more advanced):
- Allow **multiple sections** to stay open at the same time (configurable).
- Add **icons** (like + / -) that change based on expanded/collapsed state.
- Save the accordion state using **localStorage** (if reloaded, keep open sections).
- Theming: Light/Dark Mode toggle.