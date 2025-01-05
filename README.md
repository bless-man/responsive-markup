# Peer-graded Assignment: Create a Responsive Stylesheet

The goal of the final project is to create a responsive website that has three distinct views: **mobile**, **tablet**, and **large screens**. By changing the display and width of elements, you will transform the layout from:

- **One horizontal div** (Mobile View),
- To **two horizontal divs** (Tablet View),
- To **three horizontal divs** (Large Screen View).

By adding **media queries**, these changes will trigger automatically at different viewport sizes.

---

## Requirements:

### 1. Mobile View (Default)
- Use a single-column layout for mobile devices.  
- No media queries are required for this view as it serves as the default.

---

### 2. Query #1: "Tablet View" (Trigger at 772px)
- Change the page layout so that:
  - Divs are **45% of the viewport width**.
  - Images are **no more than 30% of the viewport height**.
- *(Note: You will need to change more than just the width to achieve the layout changes for the divs.)*

---

### 3. Query #2: "Large Screen View" (Trigger at 998px)
- Change the page layout so that:
  - Divs are **30% of the viewport width**.
- No other changes are required.

---

## Submission Instructions:
- Submit a responsive website meeting the above requirements.
- Use **HTML** and **CSS** to create the layout.
- Apply media queries to handle the changes in layout for different viewport sizes.

---

## Hints:
- Utilize `display: flex` or `display: grid` for layout structure.
- Use media queries (`@media`) to implement viewport-specific styles.
- Ensure images and divs maintain proportions as per the requirements.
