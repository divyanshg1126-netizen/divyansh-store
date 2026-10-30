# DivyanshStore React Project

This is the supplied DivyanshStore storefront set up as a Vite + React project with Tailwind CSS v4 and Lucide icons.

## Requirements

- Node.js LTS (includes npm): https://nodejs.org/
- Visual Studio Code: https://code.visualstudio.com/

## Run locally

1. Extract this ZIP file.
2. Open the extracted `DivyanshStore-React-Project` folder in VS Code.
3. Open **Terminal → New Terminal**.
4. Run:

   ```bash
   npm install
   npm run dev
   ```

5. Open the local URL printed in the terminal (usually `http://localhost:5173`).

## Create a production build

```bash
npm run build
```

The built site is created in the `dist/` folder.

## Important limitations

- Product information and product images are demo/sample content.
- Checkout currently simulates order placement; it does not charge cards or process UPI payments.
- Orders are not saved to a backend or database.
- The cart is stored in this browser's local storage.
- Before taking real orders, add a backend/database, order management, and a trusted payment provider.
