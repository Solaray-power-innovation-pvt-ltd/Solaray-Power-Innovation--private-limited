# Molsom Freshers' Meet — Donation Campaign

A responsive static website template for sharing information about a community Freshers' Meet donation campaign.

## Files

- `index.html` — campaign page and pledge form
- `styles.css` — responsive visual styling
- `script.js` — client-side form validation and demo pledge storage
- `node.js` — minimal Node.js static-file server

## Requirements

- Node.js 18 or newer recommended
- No third-party packages are required

## Run locally

1. Put all four files in the same folder.
2. Open a terminal in that folder.
3. Run:

   ```bash
   node node.js
   ```

4. Visit <http://localhost:3000> in your browser.
5. Press `Ctrl+C` in the terminal to stop the server.

You can also open `index.html` directly, though running the server is recommended.

## Important limitations

- This is a front-end demo. The pledge form stores entries in `sessionStorage` in the visitor's browser session only.
- No payment is taken, and pledges are not sent to the organisers or saved in a database.
- Do not collect UPI PINs, passwords, card details, or other sensitive payment information.
- Before publishing, verify the campaign name, organisers, budget, contact details, and donation instructions.
- To accept real donations, integrate a reputable payment provider on a secure backend, verify payment callbacks server-side, protect personal data, and publish appropriate privacy and refund information.

## Deployment

Deploy the folder to a static host or Node.js hosting provider. For a public campaign, use HTTPS and only publish verified organiser and payment details.

## License

Use and adapt this template for your campaign. Confirm you have permission to use any names, logos, and campaign materials.
