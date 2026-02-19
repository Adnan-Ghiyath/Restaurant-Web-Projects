# 🍽️ Restaurant Table Manager

A fully client-side Restaurant Table Management System built with pure HTML, CSS, and JavaScript. Manage tables, take orders from a menu, and print checks — all in the browser with no backend required.

---

## ✨ Features

- 🪑 **Table Management** — Open, close, and add tables dynamically
- 📋 **Interactive Menu** — Browse menu items with images, descriptions, and prices
- 🧾 **Live Order Tracking** — Add items to the selected table's order instantly
- ➕➖ **Quantity Controls** — Increase or decrease item quantities in the order
- 💰 **Live Total** — Order total updates automatically
- 🖨️ **Print Check** — Opens a print popup with the full bill, then closes the table
- 🔄 **Reset Demo** — Reset all tables back to default state
- 📱 **Responsive** — Works on mobile and desktop

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Adnan-Ghiyath/Certificate-generator.git
   ```
2. Open `Restaurent Project.html` in your browser — no server needed
3. Click on a table to select it
4. Browse the menu and click **Add** to add items to the order
5. Adjust quantities using the **+/-** buttons
6. Click **Print Check & Close Table** to print the bill

---

## 📁 Project Structure

```
Restaurent Project.html    # Main HTML structure
style.css                  # All styles and responsive layout
java.js                    # Tables, menu data, order logic, print popup
```

---

## ⚙️ How It Works

```
Select a table
      ↓
Add items from the menu
      ↓
Adjust quantities in the order panel
      ↓
Print Check → window.open() popup with full bill
      ↓
Table closes automatically
```

**Key JavaScript concepts used:**
- Dynamic DOM rendering (tables + menu cards + order rows)
- `window.open()` for print popup
- In-memory state management (no database needed)
- Event delegation for quantity controls

---

## 🛠️ Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

- Pure Vanilla JavaScript
- Zero dependencies — no npm, no frameworks
- `window.open()` for native print dialog

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made with ❤️ by [Adnan-Ghiyath](https://github.com/Adnan-Ghiyath)
