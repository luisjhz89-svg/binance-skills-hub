# PayPal setup guide

Use this guide to replace the placeholder PayPal links and support contact in the commercial landing page.

## 1) Create PayPal buttons

In your PayPal Business account:

- Go to Tools > PayPal Buttons
- Create one button for each plan:
  - Starter: $29
  - Pro: $99
  - Enterprise: $499
- Copy the generated links

## 2) Replace the placeholder links

Open `commercial/index.html` and replace:

- `TU_EMAIL_PAYPAL` with your PayPal business email or the real business account used for payments
- the generated PayPal button URLs with the actual links for each plan

## 3) Replace the contact details

Update the footer block in `commercial/index.html`:

- `tu-email@dominio.com` → your real support email
- `TU_EMAIL_PAYPAL` → your actual PayPal email or username

## 4) Test the flow

Before publishing publicly:

- click each button in a browser
- confirm it opens the PayPal checkout page
- verify the email and payment data are correct
- confirm your support workflow after payment

## 5) Support workflow after payment

For each buyer, send a short confirmation message after payment:

- access granted or invoice confirmation
- installation instructions
- support channel
- refund policy reference

Note: The recommended workflow is to send the product after successful payment confirmation from PayPal.

## 6) Important note on Enterprise

The Enterprise option should use a unique hosted button ID generated in PayPal. The generic email-based request option is used as a safe placeholder until you create the actual Enterprise checkout.
