# 🎨 Random Color Boxes

## 📘 Project Overview
This is a simple JavaScript DOM project that assigns **random background** and **text colors** to multiple boxes each time the page loads.

---

## 🧩 Features
- 5 boxes displayed using **Flexbox**.
- Each box gets:
  - A random **background color**.
  - A random **text color**.
- Colors are generated using the **RGB color format**.

---

## 🛠️ Technologies Used
- **HTML5** – Page structure  
- **CSS3** – Layout and box styling  
- **JavaScript (DOM)** – Random color generation and styling

---

## 📂 File Structure

project-folder/
│
├── index.html # Main HTML file
└── script.js # JavaScript file for random color logic


---

## 💡 How It Works
1. All `.box` elements are selected using `querySelector(".container").children`.
2. A function `getRandomColor()` generates random RGB values.
3. Each box gets a random background and text color using `style.backgroundColor` and `style.color`.

---

