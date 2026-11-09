# Shopify theme setup

This package is a Shopify Online Store 2.0 theme conversion of the current S8UL storefront prototype. It is prepared for upload as an unpublished draft. It has not been connected to or published on the live store.

## Install safely

1. In Shopify Admin, duplicate the current live theme first.
2. Go to **Online Store → Themes → Add theme → Upload zip file** and upload **S8UL-Shopify-Theme.zip**.
3. Open **Customize** on the uploaded draft. Select the actual S8UL 2026 jersey in the **S8UL header** and **S8UL home** featured product settings.
4. In Shopify Admin, create/confirm the pages and assign these templates under each page’s theme template selector: size-guide, contact-us, player-access, shipping-amp-delivery-policy, return-replacement-policy, privacy-policy, and terms-amp-conditions. Keep the store’s existing page content for the policy pages.
5. Set the Shop menu/collection, add the customer-account menu named customer-account-main-menu if using the account component, and verify the footer social links and support phone/location in the theme editor.
6. Preview the draft on desktop and phone. Place a test order using Shopify’s test payment setup and confirm variant inventory, cart, checkout, confirmation, order emails, account sign-in, and policy links. Keep the existing payment provider and fulfillment integrations configured in Shopify Admin.
7. Publish only after the store owner approves the preview and confirms products, shipping, tax, payments, domains, and existing integrations.

## How store operations work

Products, variants, inventory, prices, cart, checkout, customer sign-in, orders, payments, and fulfillment remain Shopify-native. The theme’s product form adds the selected variant to Shopify’s cart and sends the shopper to the cart; checkout is processed by the store’s configured Shopify checkout and payment providers. No custom database, payment processor, or localStorage cart is used. Account sign-in is Shopify’s hosted customer-account flow; the Player Access page displays real customer/order data when Shopify exposes a signed-in customer. More extensive custom account features require a customer-account app extension.

## Theme contents

The ZIP contains the Shopify layout, sections, JSON templates, theme settings, fonts/styles, current campaign video/poster, and size guide. It uses the current static pages as its visual source and Shopify product data for commerce. Page templates are separate so they can be assigned in Shopify Admin.

