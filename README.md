# AES Line Encryptor (Web)

A lightweight browser-based AES tool for line-by-line encryption and decryption.

## Live Demo

- Vercel: https://aes-web-tool.vercel.app/

## Features

- AES-GCM encryption/decryption using Web Crypto API
- Line-by-line processing (input and output keep the same line order)
- Import text file into input area
- Export output result to local `.txt`
- Progress bar for large batch processing

## Usage

1. Open `aes_encrypt_decrypt.html` in your browser.
2. Enter AES password.
3. Paste or import text data (one record per line).
4. Click `加密` or `解密`.
5. Export result if needed.

## Notes

- Empty lines are preserved.
- For decryption, failed lines are marked in place.
- This is a static HTML tool; no server is required.

## License

MIT

<img width="1067" height="668" alt="image" src="https://github.com/user-attachments/assets/a4e14ecf-8356-4d4f-b1e9-948a890b1438" />
