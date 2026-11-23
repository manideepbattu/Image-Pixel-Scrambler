
# Image Pixel Scrambler 🖼️

A beginner-level Python training assignment demonstrating image pixel shuffling and reconstruction using the Pillow library.

## 📌 Overview

This program loads an image, converts it into RGB pixel data, shuffles the pixels using a predefined random seed, and reconstructs the scrambled image.

It also demonstrates restoring the original pixel arrangement using the same seed.

## ✨ Features

- Load and process images using Pillow.
- Convert images into RGB format.
- Shuffle pixel data using a predefined seed.
- Reconstruct the scrambled image.
- Restore the original pixel arrangement.

## 🛠️ Technologies Used

- Python 3
- Pillow (PIL)
- Random module

## 📂 Project Structure

```text
Image-Pixel-Scrambler/
│
├── pixel_encryption.py
└── README.md
```

## ⚙️ Installation

### 1. Install Python

Install Python 3 on your system.

### 2. Install Pillow

```bash
pip install Pillow
```

### 3. Clone the Repository

```bash
git clone https://github.com/manideepbattu/Image-Pixel-Scrambler.git
```

### 4. Open the Project Folder

```bash
cd Image-Pixel-Scrambler
```

## 🚀 Usage

1. Place an image named `image.jpg` in the project folder.
2. Open `pixel_encryption.py`.
3. Run the program:

```bash
python pixel_encryption.py
```

The program generates:

- `encrypted_image.png` – Scrambled image.
- `decrypted_image.png` – Reconstructed image.

The current example uses a predefined key (`1234`) in the Python code.

## 📖 Learning Outcomes

- Basic image processing with Python.
- Understanding RGB pixel data.
- Working with Python lists.
- Using randomisation and seeded sequences.
- Reconstructing images from pixel data.

## ⚠️ Security Limitations

- This is pixel scrambling, not secure cryptographic encryption.
- Python's `random` module is not cryptographically secure.
- The example uses a hardcoded key.
- It should not be used to protect confidential images or sensitive information.

## 👨‍💻 Author

**Battu Manideep**

GitHub: [manideepbattu](https://github.com/manideepbattu)

---

*Beginner-level training assignment completed as part of cybersecurity learning.*
