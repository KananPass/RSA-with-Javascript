# RSA Encryption and Decryption Tool

A tool for RSA encryption and decryption built with JavaScript using JSEncrypt. This application allows users to generate RSA keys of various sizes (512, 1024, 2048, 4096 bits), and perform encryption and decryption operations with a clean, responsive interface using Tailwind CSS.

## Features

- **Key Size Selection**: Generate RSA keys of different sizes (512, 1024, 2048, 4096 bits).
- **Encryption/Decryption**: Encrypt and decrypt text using RSA keys.
- **Responsive Design**: Clean, responsive interface that adapts to both large screens and mobile devices.
- **Loader Integration**: Visual feedback with a loader while generating keys.

## Getting Started

### Prerequisites

To run this application, you need a modern web browser. No server-side setup is required.

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/KananPass/RSA-with-Javascript.git
    ```

2. Navigate to the project directory:
    ```bash
    cd RSA-with-Javascript
    ```

3. Open the `index.html` file in your web browser to use the tool.

### Usage

1. **Select Key Size**: Click on the buttons to select the desired RSA key size (512, 1024, 2048, 4096 bits).

2. **Generate Keys**: Click the "Generate Keys" button to generate RSA keys. While the keys are being generated, a loader will be displayed and other inputs will be disabled.

3. **Encrypt/Decrypt Text**:
   - **Encrypt**: Enter the text you want to encrypt in the "Text to Encrypt" field and click the "Encrypt/Decrypt" button.
   - **Decrypt**: To decrypt, paste the encrypted text in the "Encrypted Text" field and click the "Encrypt/Decrypt" button.

### Example Usage

1. **Generate RSA Keys**: Click on the "Generate Keys" button to create new RSA keys. The application will display a loading animation while the keys are being generated.

2. **Encryption**: Enter plain text into the "Text to Encrypt" field, then click "Encrypt/Decrypt" to see the encrypted text appear in the "Encrypted Text" field.

3. **Decryption**: Paste the encrypted text into the "Encrypted Text" field, then click "Encrypt/Decrypt" to see the decrypted text appear in the "Text to Encrypt" field.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **JSEncrypt**: For providing the RSA encryption and decryption functionality.
- **Tailwind CSS**: For the responsive and clean design.
