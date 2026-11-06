# DOXA CITY Storefront

A responsive, dark editorial-style Christian streetwear catalogue and WhatsApp ordering storefront.

## Included
- Responsive home, shop, collections, about, contact, product detail, cart and checkout views.
- Product search, collection/size/colour filters and price sorting.
- Product size, colour and quantity selection.
- Cart saved in the visitor's browser while navigating.
- Customer details and complete order message prepared for WhatsApp.
- Local product manager to add, edit, hide, mark sold out and delete products.
- JSON catalogue import/export and configurable WhatsApp contact.

## Publish
This is a static website. Upload `index.html` to the root of a GitHub repository and connect that repository to Cloudflare Pages. Use no build command and set the build output directory to `/` (or `.` if the dashboard requires a relative directory).

## Important limitations
The product manager stores catalogue edits and uploaded images in the current browser's local storage. It is suitable for previewing and managing a local copy, but edits do not automatically sync to every customer's device. A shared product dashboard requires a hosted database/CMS, image storage and admin authentication. The cart is stored locally in each customer's browser. Orders are sent to WhatsApp; no online payment gateway is included.

## Store settings
The WhatsApp number is configurable in the Product Manager page. Ghana numbers should use country code `233` and omit the leading zero. The starter setting is `233551396345`.

## Starter catalogue
The included products and fashion images are placeholders. Replace them with actual DOXA CITY product photography, descriptions, sizes, colours and prices before launch.
