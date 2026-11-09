# S8UL Official Storefront — Shopify Theme

An S8UL-branded Shopify Online Store 2.0 theme, converted from the storefront prototype in this project. The work keeps the S8UL jersey, brand colours, campaign imagery, and written content while adapting the page layouts and interaction direction to the supplied Sixes Cricket reference.

## Live preview

[Open the S8UL storefront preview](https://0x-ryo.github.io/s8ul-shopify-theme/)

This GitHub Pages version is a static visual prototype. The Shopify theme ZIP is the version intended for Shopify; real customer accounts, checkout, payments, inventory, and orders require deployment to the store’s Shopify account.

## Source websites

- Original S8UL store: https://s8ul.club/

The S8UL store and brand sites are references for the original store, merchandise, logos, colour palette, and content. Sixes Cricket is the UI/UX inspiration. This project does not reproduce Sixes branding or content.

## What is included

- Shopify theme ZIP: S8UL-Shopify-Theme.zip
- Setup and launch checklist: Shopify-Theme-Setup.md
- Online Store 2.0 JSON templates and editable Liquid sections for Home, Shop, Jersey, Size Guide, Your Bag, Player Access, Contact Us, and policy pages.
- Responsive S8UL header, navigation drawer, footer, campaign hero video, jersey product views, size chart, cart quantity controls, newsletter signup, and background pattern.
- Shopify-native product/variant selection, cart, checkout, customer sign-in, and customer order data. The theme does not implement its own database or payment processing.

## How it was built

The existing storefront pages were used as the source for the S8UL visual identity, typography, jersey details, content, and layout decisions. Their styles and campaign assets were carried into a Shopify theme structure: a shared Liquid layout, header and footer sections, page-specific Liquid sections, and JSON templates. Commerce actions were changed to Shopify product forms, cart routes, customer account features, and checkout so inventory, orders, payments, and fulfillment remain governed by the store's Shopify configuration.

## Before deployment

Upload the ZIP as an unpublished theme, set the featured jersey product, assign the included templates to the corresponding Shopify pages, configure the account menu and support/social links, and verify checkout and customer sign-in in a preview. See Shopify-Theme-Setup.md for the checklist. The theme has not been connected to or published on the live S8UL store.

