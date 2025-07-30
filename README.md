#  Handwriting Text to Image Generator

This Python script converts custom text into an image that mimics handwriting. It supports RGB color customization and wraps long text into multiple lines.

---

## Sample Output


<img width="651" height="229" alt="hand" src="https://github.com/user-attachments/assets/2215acbc-6666-4f93-bc37-ff9647b09cb7" />
<img width="554" height="148" alt="han" src="https://github.com/user-attachments/assets/2b323778-f8c8-48c4-95de-f186e3a74200" />




---

## Features

- Convert any text into an image with a "handwritten" appearance
- Choose your own RGB color for the text
- Auto-wraps long paragraphs into neat lines
- Saves output image as `handwriting_output.png`

---

## Requirements

Install the required library:

```bash
pip install pillow
```

---

---

## How to Run

1. Save the script as `handwriting_generator.py`
2. Make sure `arial.ttf` or a custom `.ttf` font exists in your directory.
3. Run the script using:

```bash
python handwriting_generator.py
```

4. Enter your text and RGB values when prompted.
5. Your handwritten-style image will be saved in the current directory.

---

##  Notes

- You can use a custom handwriting font for a more realistic look.
- RGB input outside the valid range (0-255) falls back to a default blue.
- You can extend this project to support multi-page or styled fonts easily.

---
