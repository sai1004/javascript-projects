## **Modal Popup Window – Project Requirements**

### **Core Functionalities**
1. **Open Modal**  
   - Clicking a button (e.g., "Open Modal") should open a modal popup centered on the screen.
   
2. **Close Modal**
   - Modal should close when:
     - Clicking the close button (e.g., "×" icon inside the modal).
     - Clicking outside the modal (on the overlay/background).

3. **Overlay Background**
   - A semi-transparent dark background should appear behind the modal to highlight the popup.

4. **Responsive Design**
   - Modal should look good on desktop, tablet, and mobile screens.

5. **Smooth Animations**
   - Add a simple **fade-in** and **fade-out** animation when opening and closing.

---

### **Technical Requirements**
- Use **HTML**, **CSS**, and **Vanilla JavaScript** (no frameworks like React, Angular, etc.).
- JavaScript should handle:
  - Showing/hiding the modal.
  - Adding/removing the overlay effect.
  - Managing click events (open/close).

---

### **Bonus Features (Optional if you want to go further)**
- **Esc key close**: Pressing the `Esc` key should also close the modal.
- **Multiple modals**: Support more than one modal if clicked from different buttons.
- **Draggable modal**: Allow dragging the modal around the screen.
- **Auto-close modal** after a few seconds (optional timer feature).
- **Trap focus inside modal** for accessibility (advanced).