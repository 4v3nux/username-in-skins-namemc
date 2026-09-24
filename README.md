# Minecraft Namemc Picture Generator

> An automatic Python script for generating a set of Minecraft skins based on an image map (`map.png`). The script slices the pattern into blocks and embeds them in the base skin texture.

---

## Features

* **Automatic slicing:** Quickly create multiple skins from a single graphic file (`map.png`).
* **Batch processing:** Save the finished results to a separate folder `skins`.
* **Lightweight:** Minimal dependencies; the standard Pillow image processing library is used.
* **Flexibility:** Easy customization of the template to suit any needs.

---

## Project structure

* `create.py` — the main script for slicing and generating skins.
* `skin.png` — the base Minecraft skin template.
* `map.png` — the original image with fragments (**size: 72x24 pixels**, the first 8x8 pixels are skipped).
* `skins` — the folder where the generated skins are automatically saved (`skin_1.png`, `skin_2.png`, etc.).

---

## Requirements and installation

Make sure you have **Python** installed and the required Pillow library:

```bash
pip install Pillow
