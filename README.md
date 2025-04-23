# JWT Decoder & Validator

A simple, client-side tool to decode JSON Web Tokens (JWT) and optionally validate the signature using a shared secret (`HS256` only). Built with vanilla HTML, CSS, and JavaScript — and deployable via GitHub Pages.

![JWT Decoder Screenshot](./screenshot.png)

## ✨ Features

- Paste in a JWT to decode its Header, Payload, and Signature.
- Optionally input a secret to verify the signature (`HS256` only).
- Color-coded validation feedback.
- Fully browser-based — no data is sent to any server.

## 🧪 Try It Live

👉 [https://danielgale.github.io/jwt-decoder](https://danielgale.github.io/jwt-decoder)

## 🛠 Usage

1. Paste your JWT into the provided textarea.
2. Optionally enter the secret used to sign the JWT.
3. Click **"Decode & Validate"** to see decoded sections and validation result.

## 📝 Example

Sample token format:

```
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c
```

## 🚀 Deployment

1. Fork or clone this repo.
2. Push an `index.html` file to your repository.
3. Enable GitHub Pages via **Settings > Pages**.
4. Choose branch `main` and root folder `/`.

Your tool will be live at: `https://<your-username>.github.io/jwt-decoder`

## 🛡️ Notes

- Signature validation supports only `HS256`.
- Uses [Web Crypto API](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto) for validation.
- Will not work with RS256, ES256, or asymmetric algorithms.

## 📄 License

MIT License — feel free to fork, modify, and share!
