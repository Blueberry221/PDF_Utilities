## 📄 `compress_pdf.py` – Compress PDF with Ghostscript

This Python script allows you to **compress PDF files** using **Ghostscript**, making your documents smaller without significant loss in quality.

---

### ✅ Features

* Compresses PDF files using Ghostscript
* Supports various compression levels: `screen`, `ebook`, `printer`, `prepress`, `default`
* Produces a smaller output PDF while maintaining readability

---

### ⚙️ Requirements

* **Python 3.8+**
* **Ghostscript** installed on your system

  > 🔗 [Download Ghostscript](https://www.ghostscript.com/download/gsdnld.html)

Make sure the Ghostscript path in the script matches your system:

```python
ghostscript_path = r"C:\Program Files\gs\gs10.05.1\bin\gswin64c.exe"
```

---

### 🚀 How to Use

1. Save the script as `compress_pdf.py`
2. Import and use the function in your Python code:

```python
compress_with_ghostscript("input.pdf", "output.pdf", quality="ebook")
```

Available `quality` levels:

| Quality    | Description                            |
| ---------- | -------------------------------------- |
| `screen`   | Lowest quality, smallest file size     |
| `ebook`    | Medium quality, suitable for e-books   |
| `printer`  | High quality for printing              |
| `prepress` | Very high quality for press production |
| `default`  | Ghostscript’s default settings         |

---

### 📃 License

Released under the **MIT License** – free to use, modify, and distribute.

---

### 🙋‍♂️ Author

Created by **Petrus Dennis Artanto**
📧 [frozendsp@gmail.com](mailto:frozendsp@gmail.com)

---
