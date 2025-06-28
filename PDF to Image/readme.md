## 🖼️ `convert_pdf_to_images.py` – Convert PDF Pages to Images (PNG)

This Python script allows you to **convert each page of a PDF file into separate image files** (in PNG format) using the `pdf2image` library and **Poppler**.

---

### ✅ Features

* Converts every page of a PDF into a `.png` image
* Automatically creates an output folder (if not existing)
* Useful for document preview, OCR preprocessing, or image-based analysis

---

### ⚙️ Requirements

* **Python 3.8+**
* **Poppler for Windows**

  > 🔗 [Download Poppler](http://blog.alivate.com.au/poppler-windows/)

Make sure the `poppler_path` in the script points to the `bin` directory of your Poppler installation:

```python
poppler_path = r"C:\poppler-24.08.0\Library\bin"
```

Install the required Python package:

```bash
pip install pdf2image
```

> On first use, you may also need to install `Pillow`:
>
> ```bash
> pip install Pillow
> ```

---

### 🚀 How to Use

1. Save the script as `convert_pdf_to_images.py`
2. Import and call the function in your own script:

```python
convert_pdf_to_images("document.pdf", "output_images")
```

This will create images like:

```
output_images/
├── page_1.png
├── page_2.png
└── ...
```

---

### 📃 License

Released under the **MIT License** – free to use, modify, and distribute.

---

### 🙋‍♂️ Author

Created by **Petrus Dennis Artanto**
📧 [frozendsp@gmail.com](mailto:frozendsp@gmail.com)

---