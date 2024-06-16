# URL to QR Code Generator

This project uses Node.js to accomplish three tasks:
1. Get user input using the `inquirer` npm package.
2. Convert the user-entered URL into a QR code image using the `qr-image` npm package.
3. Save the user input to a text file using the native `fs` module.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed [Node.js](https://nodejs.org/en/download/) (which includes npm).

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Navigate to the project directory:
   ```sh
   cd your-repo-name
   ```

3. Install the dependencies:
   ```sh
   npm install inquirer qr-image
   ```

## Usage

To use this project, follow these steps:

1. Run the script:
   ```sh
   node index.js
   ```

2. You will be prompted to enter a URL:
   ```sh
   Type in your URL: 
   ```

3. After entering the URL, the following will happen:
   - A QR code image (`qr_img.png`) will be generated and saved in the project directory.
   - The entered URL will be saved to a text file (`URL.txt`).

## Acknowledgements

- [inquirer](https://www.npmjs.com/package/inquirer)
- [qr-image](https://www.npmjs.com/package/qr-image)
- [Node.js fs module](https://nodejs.org/api/fs.html)
