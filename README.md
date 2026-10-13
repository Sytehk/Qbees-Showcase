# Qbees

**A curated fashion storefront with a complete commerce workflow**

Qbees is a single-store fashion commerce project built around two connected experiences: a polished storefront for shoppers and an operations workspace for the team running the store.

The customer experience is designed to make product discovery clear and editorial. The store can present curated collections alongside searchable catalog pages, detailed product pages, and a checkout journey that carries a selected product and variant through to an order.

## Shopping journey

- Browse editorial collections and the full product catalog.
- Search, filter, and sort products.
- Review product descriptions, imagery, and available variants such as size or colour.
- Save products for later and maintain a shopping cart.
- Check out, review order details, and follow delivery progress.
- Request a return when eligible or contact the store through a support conversation.

Product variants and inventory matter throughout the journey: the selected size or colour needs to remain connected to the cart and order, and availability should be clear before the customer checks out. The store also includes account details, addresses, recently viewed products, and customer-facing order history.

## Store operations

The administration experience supports the work behind the storefront: maintaining products and variants, organizing collections and categories, tracking inventory, processing orders, reviewing returns, responding to customer messages, and updating store content.

The platform is designed for one store owner to work with multiple administrators. Team access and permissions allow operational duties to be shared while keeping critical store, payment, and security controls restricted to authorized roles. Store settings, media assets, discounts, and operational reporting sit alongside the day-to-day catalog and fulfillment work.

The product is intentionally a single-store platform rather than a multi-vendor marketplace. That lets the customer catalog, inventory, checkout, and fulfillment processes follow one store's policies while supporting delegated work by staff.

## Storefront visual

<p align="center">
  <img src="assets/storefront-editorial.jpg" width="720" alt="Editorial fashion image used by the Qbees storefront">
</p>
<p align="center"><sub>Storefront image asset from the project. This is product imagery, not a UI screenshot.</sub></p>

## Engineering

The storefront and administration tools use Next.js and TypeScript. Supabase and PostgreSQL support accounts and application data; Stripe is used for payment integration. The platform also includes validation and access-control work for owner and administrator operations, plus browser workflow tests for core shopping and admin journeys.

## Technology

Next.js, TypeScript, Supabase, PostgreSQL, Stripe, and browser workflow tests.

## This repository

This is a public project overview with one storefront image asset. It does not include private source code, customer or order data, credentials, or internal operating configuration.

[Explore AceNetics](https://acenetics.dev)
