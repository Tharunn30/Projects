---

# QR Code Generator

This Python script generates a QR code from a given URL or link, allowing you to customize the QR code's fill and background colors. The generated QR code is saved as a PNG file.

## Features

- Generates a QR code from a user-provided URL or text.
- Customizable fill color and background color.
- Saves the QR code as a PNG file.

## Prerequisites

Before running the script, ensure you have Python installed and the necessary libraries:

- Python 3.x
- `qrcode` library
- `Pillow` library

You can install the required libraries using pip:

```bash
pip install qrcode[pil] Pillow
```

## Usage

1. Clone the repository or download the script:

```bash
git clone https://github.com/your-username/qrcode-generator.git
cd qrcode-generator
```

2. Run the script:

```bash
python qrcode_generator.py
```

3. The script will prompt you to enter:
   - The link or text you want to convert into a QR code.
   - The fill color of the QR code (in HEX format, e.g., `#000000` for black).
   - The background color of the QR code (in HEX format, e.g., `#FFFFFF` for white).
   - The filename to save the QR code as (without the file extension).

4. The generated QR code will be saved as a PNG file in the current directory with the specified filename.

## Example

Here is a sample interaction:

```bash
Enter the link you want to convert into QR code: https://example.com
Enter the fill color for the QR code (in HEX format): #000000
Enter the background color for the QR code (in HEX format): #FFFFFF
Enter the filename to save the QR code as (without extension): example_qr

QR code saved as example_qr.png
```

This will generate a QR code with a black fill color and a white background, saved as `example_qr.png`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributions

Contributions are welcome! Feel free to submit a pull request or open an issue if you encounter any problems or have suggestions for improvements.

---
