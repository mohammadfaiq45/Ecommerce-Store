# BrandVerse — Single-Vendor E‑commerce Website

## Project Summary

BrandVerse is a responsive, single-vendor storefront built for small-to-medium physical shops that want a polished online presence. The product focuses on an easy shopping experience, secure checkout, simple inventory management for the owner, and an admin panel to manage products, categories, orders, customers, and discounts.

---

## Key Goals

- Represent the shop online with a modern, trust-building UI.
- Fast browsing & search for large catalogs.
- Simple secure checkout (Bank Transfer, cash on delivery).
- Admin interface for inventory, order, and customer management.
- Mobile-first responsive layout for customers on phones.

---

## Core Features

### Customer (Public)
- Home / Hero section with promos and categories
- Category & product listing (filter, sort, pagination)
- Product detail page (images, carousel, specs, reviews)
- Search with auto-suggest
- Cart and multi-address checkout (guest + account checkout)
- Order confirmation email & order tracking
- User accounts: profile, addresses, order history
- Wishlist / Save for later

### Admin (Private)
- Product CRUD (title, SKU, images, variants, price, stock)
- Category / subcategory management
- Order management (status updates)
- Basic sales dashboard (orders, revenue, top-sellers)
- Coupon/discount management
- Customer management and messaging

---

## Tech Stack

- **Frontend:** Next.js (React) — server-side rendering + static export where beneficial
- **Styling:** Tailwind CSS (fast, modular) + responsive utility classes
- **Backend/API:** Node.js + Express (REST) or Next.js API routes
- **Database:** MongoDB (Atlas) for flexible product schema
- **Authentication:** JWT + secure httpOnly cookies (or NextAuth for Next.js)
- **Payments:** bank transfer handle by admin, plus Cash On Delivery
- **Image storage:** Cloudinary
- **Email:** nodemailer
- **Hosting:** Vercel for Next.js frontend, Render/Heroku or VPS for API (or host both on Vercel + serverless functions)


