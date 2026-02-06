# Billing Strategy - Chapel Web Solutions

Using **Stripe Dashboard** as a standalone billing solution. No custom integration needed.

## Invoicing

- Create invoices directly in Stripe Dashboard
- Add line items, due dates, and notes
- Stripe emails the invoice to your client with a "Pay Now" button
- Client pays on Stripe's hosted payment page (cards + ACH bank transfers)
- Automatic reminders for overdue invoices
- Payment notifications when paid

## Subscriptions

Perfect for the "Build and Maintain" tier with ongoing monthly fees.

- Create subscription products (e.g., "Website Maintenance - $50/month")
- Set billing interval (monthly, yearly, etc.)
- Send subscribe link to client
- Stripe automatically charges each billing cycle
- Handles failed payments and retries automatically

## Suggested Workflow

1. **Initial project**: Create a one-time invoice for the build/deploy work
2. **Ongoing maintenance**: Set up a recurring subscription for monthly maintenance
3. **Ad-hoc work**: Invoice as needed for additional requests

## Customer Self-Service

Stripe has a built-in **Customer Portal** (no code required) where clients can:
- View their invoices and payment history
- Update their payment method
- Manage or cancel subscriptions

Enable it in Stripe Dashboard under Settings > Customer Portal.

## Getting Started

1. Sign up at [stripe.com](https://stripe.com)
2. Complete account verification
3. Create your first product/price in the Products section
4. Send your first invoice from the Invoices section
