### 1. **Basic Requirements**
- A simple webpage with **some content** (e.g., headings, text, buttons).
- A **toggle switch** or **button** to switch between Light Mode and Dark Mode.
- When toggled:
  - The **background color**, **text color**, and maybe other **UI elements** should change accordingly.
- Use **pure JavaScript**, **HTML**, and **CSS** (no frameworks).

---

### 2. **Functional Requirements**
- Default theme: Light Mode (or based on user system preferences using `prefers-color-scheme`).
- When user clicks the toggle:
  - If current theme is Light, switch to Dark.
  - If current theme is Dark, switch to Light.
- Remember the user's choice:
  - Save the selected theme in **localStorage**.
  - On page reload, **apply the saved theme**.

---

### 3. **UI/UX Requirements**
- Smooth transition (add CSS transitions for background and text color).
- A clear and accessible toggle button:
  - Example: a sun/moon icon, a switch slider, or a simple button.
- Toggle should be **keyboard accessible** (e.g., `tabindex`, `keypress`).

---

### 4. **Optional (Bonus) Features**
- Detect and apply **system default theme** automatically.
- Add **animations** when switching themes.
- Provide multiple theme options, e.g., Light / Dark / Auto.
- Show a notification (like a toast) when theme changes.

---

### 5. **Technical Stack**
- HTML5
- CSS3 (can use variables like `--bg-color`, `--text-color`)
- Vanilla JavaScript
