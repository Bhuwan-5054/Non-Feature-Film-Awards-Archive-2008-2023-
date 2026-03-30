# 🎬 Non-Feature Film Awards Archive (2008–2023)

A clean, responsive, and structured web-based archive of Non-Feature Film Awards from 2008 to 2023.
This project allows users to explore award categories year-wise, view winners, read synopses, and directly access the corresponding document pages.

---

## 🚀 Features

* 📅 Year-wise structured award data (2008–2023)
* 🏆 Category-based award listing
* 📖 Synopsis support for each award
* 🔗 Direct page linking to PDF (per award)
* 📱 Fully responsive (Mobile + Desktop)
* ⚡ Fast and lightweight (Vanilla JS)

---

## 🗂️ Project Structure

```
project/
│
├── index.html        # Main UI structure
├── style.css         # Styling (UI/UX)
├── script.js         # Data + logic
├── assets/           # Images / icons (optional)
├── data.pdf          # Source document (your PDF)
└── README.md
```

---

## 🧠 How It Works

* All award data is stored in a structured JavaScript object (`script.js`)
* Each year contains:

  * Category name
  * Winner (to be filled)
  * Synopsis (to be filled)
  * Page number (linked to PDF)
* Clicking **"Open Page"** navigates to the exact page in the PDF

---

## 🛠️ Setup & Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Open the project folder:

   ```bash
   cd your-repo-name
   ```

3. Run the project:

   * Simply open `index.html` in your browser

---

## 📌 Customization

You can easily update:

* 🏆 Winners → inside `script.js`
* 📖 Synopsis → inside `script.js`
* 📄 PDF file → replace `data.pdf`
* 🔗 Page links → auto-handled via page numbers

---

## 📄 PDF Integration

Make sure your PDF is placed correctly:

```
/data.pdf
```

And your page button uses:

```
data.pdf#page=PAGE_NUMBER
```

---

## 💡 Future Improvements

* 🔍 Search functionality (by film/category)
* 🎯 Filter by category
* 🌐 Deploy as live website
* 🎨 UI animations & transitions
* 🧾 Multi-winner support UI

---

## 📷 Preview

*Add screenshots of your website here*

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is for educational and informational purposes.

---

## 👨‍💻 Author

**Your Name**

* GitHub: https://github.com/your-username

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
