# QR Code Generator

## Description

QR Code Generator is a simple command-line tool that allows users to generate QR codes for URLs. Users can input a URL, and the tool creates a corresponding QR code image and saves the URL in a text file.

## Technologies Used
- Node.js
- JavaScript
- Inquirer (for user input)
- qr-image (for generating QR codes)
- fs (for file system operations)

## Usage

1. Run the script.
2. Enter the URL when prompted.
3. The tool will generate a QR code image and save the URL in a text file.

## Installation
1. Clone the repository:

```bash
 git clone https://github.com/samuelcardenasg23/qr-code-generator
```
2. Install dependencies:
```bash
npm i inquirer qr-image
```
3. Run the generator:
```bash
node index.js
```