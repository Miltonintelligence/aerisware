# Product

<!-- impeccable:product-schema 1 -->

> Status: drafted by `/impeccable init` from repository evidence only. The owner skipped the interview, so every line marked *(inferred)* is unconfirmed. Everything under **Open decisions** needs an answer before new surfaces are designed.

## Platform

web

## Stack

Static HTML/CSS: a single self-contained `index.html` with inline styles, no build step or framework. *(inferred from the repo; hosting target not confirmed)*

## Users

- **Shop customers**: people buying made-to-order dog-themed gifts from the AerisWare Etsy shop, reading this site to understand how their order data is handled. *(inferred from `index.html`)*
- Whether the core buyer is a dog owner buying for themselves or a gift giver buying for someone else: **open**.

## Product Purpose

AerisWare sells made-to-order dog-themed gifts through its Etsy shop. This repository currently hosts the shop's public legal pages (a privacy policy, effective July 8, 2026), which the shop and its marketing platforms can link to. What success means for the site beyond meeting that need: **open**.

## Positioning

**Open.** Nothing in the repository says why a buyer would choose AerisWare over other dog-gift shops (for example personalization, an original art style, breed coverage, or price). Future work must not invent a differentiator.

## Operating Context

- **Etsy** is the marketplace, checkout, payment processor, and customer-messaging channel ("Message Seller").
- **Printify** and its print providers produce and ship each item made to order; they receive the customer's name, shipping address, and order details.
- **Shipping carriers** deliver orders.
- **Pinterest** is the marketing channel; the shop sees only aggregate pin and link performance.
- Customers may add personalization text to an order.

## Capabilities and Constraints

- AerisWare never collects or stores payment card details; Etsy handles payment.
- AerisWare does not sell personal information.
- The shop is intended for adults and does not knowingly collect data from children under 16.
- Legal copy references GDPR (EU/UK) and CCPA (California) rights, so readers may be international.
- The privacy policy still carries a "general template" disclaimer asking the owner to verify it against real practices. It has not been confirmed as final legal text.

### Open decisions

1. **Site scope:** legal pages only, a brand site that links to Etsy, or a future direct storefront?
2. **Primary buyer:** self-purchasing dog owners, gift givers, or both?
3. **Differentiator:** what AerisWare offers that neighboring shops cannot truthfully claim.
4. **Product range:** which item types are sold (not stated anywhere in the repo).
5. **Hosting / domain** for this site.

## Brand Commitments

- **Name:** AerisWare (one word, capital A and W).
- **Mark:** a five-band concentric rainbow arch in terracotta-to-cream tones (inline SVG in `index.html`). *(existing asset; not yet confirmed as the official logo)*
- **Voice** in existing copy: plain, direct, and reassuring ("We do not sell your personal information").
- **Public contact:** Etsy "Message Seller", or miltonintelligence@gmail.com.

## Evidence on Hand

- `index.html`: the complete privacy policy and the arch mark.
- **Not in the repository, so it must not be fabricated:** product photos, a product catalog, prices, reviews or testimonials, sales figures, shipping times, a returns or refund policy, terms of service, or an Etsy shop URL.

## Product Principles

1. **Etsy is the source of truth for commerce.** Orders, payment, and messaging happen on Etsy; this site must never contradict it or imply a checkout it doesn't have. *(inferred)*
2. **Trust through plain language.** Legal and policy content should be easy for an ordinary shopper to read and act on.
3. **Say only what is true.** Product claims, reviews, and policies appear only when the owner has supplied or confirmed them.
