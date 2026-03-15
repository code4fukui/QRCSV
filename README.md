# QRCSV

QRCSV is a format for encoding CSV data in QR codes.

## Demo
The project includes a web-based QR code reader and generator.

## Features
- Read CSV data from QR codes
- Generate QR codes from CSV data

## Usage
To read CSV data from a QR code:
1. Open the web page
2. Point the camera at the QR code
3. The CSV data will be displayed in a table

To generate a QR code from CSV data:
1. Include the QR code script in your HTML:
   ```html
   <script type="module" src="https://code4fukui.github.io/qr-code/qr-code.js"></script>
   ```
2. Insert the CSV data between `<qr-code>` tags:
   ```html
   <qr-code>CSV,HCR_1
   身長,176.0
   体重,64.7
   標準体重,68.1
   </qr-code>
   ```

## License
This project is licensed under the MIT License.