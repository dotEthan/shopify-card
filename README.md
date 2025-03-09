# Shopify Product Card

Repo for hosting a product card project using Shopify.

Preview available here: https://dotethan-co.myshopify.com/?_ab=0&_fd=0&_sc=1

## Updated/Created Files 

Only those files updated by me will be using tailwindcss as base theme did not. Base theme was "Dawn", as the ask was to just show the product card, I did not clean out the extra files. 

### Templates

- index.json -  Minimal changes to allow a simple display of a single product in the product-list on the front page for easy viewing.

### Sections

- product-list.liquid -  Created a simple for loop to display the card with basic formatting. 

### Snippets

- product-card.liquid - Created do include all product-card code. I left the Javascript code in the file as it was all tightly coupled and, while it's getting longer (~150 lines), it's still quite readable. If I was adding more, I'd likely move it to it's own file. 

### Styling

- Created src/tailwind.css to add extra styles and variables, all of which is compiled to application.css. I included both in my commits for clarity. 

## Tech Stack

The base template (Dawn) uses [Remix](https://remix.run). The following libraries and Shopify tools are also included to ease app development:

- [TailwindCSS](https://tailwindcss.com/): CSS Framework to allow for quick development
- [Shopify App Remix](https://shopify.dev/docs/api/shopify-app-remix) provides authentication and methods for interacting with Shopify APIs.
- [Shopify App Bridge](https://shopify.dev/docs/apps/tools/app-bridge) allows your app to seamlessly integrate your app within Shopify's Admin.
- [Polaris React](https://polaris.shopify.com/) is a powerful design system and component library that helps developers build high quality, consistent experiences for Shopify merchants.
- [Webhooks](https://github.com/Shopify/shopify-app-js/tree/main/packages/shopify-app-remix#authenticating-webhook-requests): Callbacks sent by Shopify when certain events occur
- [Polaris](https://polaris.shopify.com/): Design system that enables apps to create Shopify-like experiences
