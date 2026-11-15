# ShopScale - Architecture Decisions

## 1. Architecture

- Modular Monolithic Architecture
- React frontend
- Express backend
- PostgreSQL database

## 2. User Roles

- CUSTOMER
- SELLER
- ADMIN

## 3. Seller Registration

- Seller applications require admin approval.
- Approved sellers receive seller permissions.

## 4. Payments

- Simulated payments.
- One combined payment per parent order.
- No real payment gateway initially.

## 5. Orders

- One parent order per customer checkout.
- Multiple seller-specific suborders.
- Seller-specific shipment tracking.

## 6. Shipping

- Seller-managed shipping.
- Simulated courier and tracking information.

## 7. Cancellation

- Partial cancellation supported.
- Eligible inventory restored.
- Simulated refunds recorded separately.

## 8. Technology Decisions

- React + Tailwind CSS
- Node.js + Express.js
- PostgreSQL + Prisma
- Redis
- Docker Compose
- Cloudinary

## 9. Development Constraint

- Interview-oriented portfolio project.
- Target completion: 6-8 weeks.
- Avoid unnecessary production infrastructure.